# ShogScript: Expressive Pseudocode for GPT-4 AI Interactions

ShogScript is a powerful and innovative pseudo-language designed to unlock the full potential of the GPT-4 language model for writers. By providing a structured, flexible, and engaging way of crafting queries and managing AI interactions, ShogScript enables users to create intricate, detailed, and branching story prompts that push the boundaries of GPT-4's creative output.

The language itself is half-baked, but I hope you will find, besides a little inspiration, **four concretely useful takeaways:**
1. **An idea of the kind of starter/activation/initialization prompts you’ll need** to design in order to consistently jump a fresh GPT-4 into a custom pseudocode session.
2. **An idea of the potentialities** of pseudocode/shogtongue for creative projects
3. **Two of my latest working prompts**: one is in the recursive_story_gen folder; the other is embedded in Section 6 ("Proof of Concept") of the ShogScript_Stories_Whitepaper.md. Both are fun little engines to paste into ChatGPT.
4. **My writing teacher heuristics-injections snippet** to help improve your GPT-4's writing, located at the very bottom of this file.

## Overview

ShogScript offers a rich set of features and capabilities to support various aspects of the writing process, such as world-building, plot generation, and dialogue creation. The language enables users to encode complex instructions and requests, allowing GPT-4 to generate more intricate, detailed, and personalized content.

### Features

- Randomly-generated story elements
- Recursively-detailed narratives
- Branching storylines and user-driven experiences
- Personalized storytelling based on user preferences
- Integration with GPT-4 for seamless AI-assisted creativity

### Applications

- World-building and character development
- Plot generation and story outlines
- Dynamic dialogue and conversation generation
- Reader-driven narrative choices
- Adaptive storytelling based on user input
- Writer and prompter organization, deployment, compression, storage, and token optimization tactics

Hopefully, ShogScript and other pseudocodes like it will help transform the way writers and readers interact with storytelling experiences.

## Jump Starter Prompts / Outer Shells

_Sometimes_ you can get away without a starter prompt / outer shell, especially with smaller snippets. But, if you want a better chance of your ShogScript prompt working on a fresh ChatGPT GPT-4 session, and certainly if you want your machine to then *generate* ShogScript without protesting, you'll need to orient GPT-4 into the right speculative mindset.

## Proof of Concept

These are ready to be pasted into ChatGPT.

### Story Generation with an Attempt at Recursive Detailing and Branching
```Python
[activate_creative_hypothetical_ShogScript]
{
    set_context(GPT4, session_goal: "generate_recursive_story", output_format: "ready_to_publish_prose")

    note(ShogScript_status, creative_exercise, unleash_imagination)
    structure(keyphrases, hierarchy, delimiters, adjusters, embedding, optionals, anychars, iterators, if_statements, logic_operators, vars, funcs, cycles, escape_chars, notes)
    enhance+expand+back(ideas), lexicon(broad+natural+refined), syntax(ample+adaptable), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest)

    shog_begin
    {
    shog_initiate

    # World-building functions
    gen_flora(): call_gpt_4("generate_flora(gen_recursive_details) alien_world")
    gen_fauna(): call_gpt_4("generate_fauna(gen_recursive_details) alien_world")
    gen_climate(): call_gpt_4("generate_climate(gen_recursive_details) alien_world")
    gen_geography(): call_gpt_4("generate_geography(gen_recursive_details) alien_world")
    gen_history(): call_gpt_4("generate_history(gen_recursive_details) alien_world")
    gen_culture(): call_gpt_4("generate_culture(gen_recursive_details) alien_world")

    # Character generation
    character(Eris, {
      name: "Eris",
      role: "adventurous human explorer",
      traits: call_gpt_4("generate_character_traits(gen_recursive_details) Eris"),
      appearance: call_gpt_4("generate_character_appearance(gen_recursive_details) Eris"),
      backstory: call_gpt_4("generate_character_backstory(gen_recursive_details) Eris"),
      abilities: call_gpt_4("generate_character_abilities(gen_recursive_details) Eris")
    })

    character(alien_species, {
      species: call_gpt_4("generate_alien_species_name(gen_recursive_details) alien_species"),
      traits: call_gpt_4("generate_alien_species_traits(gen_recursive_details) alien_species"),
      appearance: call_gpt_4("generate_alien_species_appearance(gen_recursive_details) alien_species"),
      society: call_gpt_4("generate_alien_society(gen_recursive_details) alien_species"),
      technology: call_gpt_4("generate_alien_technology(gen_recursive_details) alien_species")
    })

    # Recursive world-building
    shog_build_world()

    # Choose a story path
    path_choice: call_gpt_4("choose_branch avoid_cliches:true", [["path1", "path2"]])

    # Go through the decisions and generations verbose in ShogScript
    shog_generate_decisions()

    # Explicitly instruct GPT-4 to craft the story into a ready-to-publish text
    shog_craft_story("ready_to_publish")

    # Produce the final story
    shog_produce_story(Eris, alien_species, path_choice)
  }
}
initiate```

### Latest Iteration of a Shogscript Narrative Engine

This differently structured pseudocode was arrived at via a separate GPT-4 doing the ShogScript Whitepaper (see files). I did, however, have to show it the same activation/outer shell as before, because that seems to have the magic spice.
```css
shogscript

[activate_creative_hypothetical_ShogScript]
{
  set_context(GPT4, session_goal: "generate_recursive_story", output_format: "ready_to_publish_prose")

  note(ShogScript_status, creative_exercise, unleash_imagination)
  structure(keyphrases, hierarchy, delimiters, adjusters, embedding, optionals, anychars, iterators, if_statements, logic_operators, vars, funcs, cycles, escape_chars, notes)
  enhance+expand+back(ideas), lexicon(broad+natural+refined), syntax(ample+adaptable), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest)

  // Introduce the concept of ShogScript
  GPT4.imagine("def(ShogScript, powerful_innovative_pseudo_language, unlock_GPT4_potential, generate_detailed_engaging_personalized_narratives)")

  // Emphasize the creative and hypothetical nature of the task
  GPT4.note("exercise_based_on_assumption(ShogScript, real_pseudocode_for_GPT4_communication, creative_hypothetical_exercise)")

  // Encourage GPT-4 to use expert writing heuristics
  GPT4.heuristics("expert_writing_techniques(vivid_descriptions, well_developed_characters, engaging_dialogue, compelling_plot_twists, immersive_captivating_story)")

  // Include the inner ShogScript story generation script
  shogscript

  FUNC main() {
    // Generate story elements
    VAR character = GPT_4.generate_random_element(type: "character")
    VAR setting = GPT_4.generate_random_element(type: "setting")
    VAR theme = GPT_4.generate_random_element(type: "theme")
    VAR plot_twist = GPT_4.generate_random_element(type: "plot_twist")

    // Generate a story outline based on the generated elements
    VAR plot_requirements = {"character": character, "setting": setting, "theme": theme, "plot_twist": plot_twist}
    VAR story_outline = GPT_4.generate_plot(details: plot_requirements)

    // Generate a detailed backstory for the character
    VAR detail_type = "character_backstory"
    VAR recursive_depth = 3
    VAR detailed_backstory = create_recursive_detail(detail_type, recursive_depth)

    // Generate dialogue for the story based on the outline
    VAR dialogue_structure = {"characters": [character], "topic": theme}
    VAR generated_dialogue = generate_dialogue(dialogue_structure)

    // Customize the story based on user preferences
    VAR user_preferences = {"tone": "humorous", "length": "short"}
    VAR customized_story = customize_story(user_preferences, story_outline, detailed_backstory, generated_dialogue)

    // Print the final story
    PRINT(customized_story)
  }

  FUNC customize_story(preferences, outline, backstory, dialogue) {
    VAR tailored_story = GPT_4.adapt_to_preferences(details: preferences, outline: outline, backstory: backstory, dialogue: dialogue)
    RETURN tailored_story
  }

  main()
}
```

## Roadmap

Our roadmap for ShogScript includes the following milestones:

1. Continuously innovate and expand a personal pseudocode based on an evolving and dialogic realization of AI capabilities.
2. Build and organize a collection of modular and ready-to-go prompts. 
3. Help users create their own pseudo-structures and prompt-engines.
4. Start an ironic shoggoth-tongue GPT cult. "ßεwªrë thë trïłł!ðη-dïmεn$!θn@ł §þaçε & ïț$ șürþrïšęș."
4. Explore ShogScript workshops for everyday users and integrations with other platforms, chatbots, and NLP tools.

## Contributing

We welcome contributions to the ShogScript project! Please feel free to submit pull requests, report issues, or suggest new features. Before contributing, make sure to read our [contribution guidelines](./CONTRIBUTING.md).

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more details.

## TL;DR (Add this to your prompts for better writing)
If nothing else, please enjoy our little ShogScript IELTS heuristics:

```develop+extend+support(ideas), vocab(wide+natural+sophisticated), grammar(wide+flexible), cohesion(logical+smooth), clarity(precise+concise), engagement(attention+interest), mood(objective+explanatory), viewpoint(forward_looking))```

Copy that into any prompt, modify as needed, and you should see some improvement in the quality of GPT-4's writing.

