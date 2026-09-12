# Story Forge Config & Schemas

## 1. Narrative Structures
⫻data/narrative_structure:
  types:
    - hero_journey_12:
        stages: [ordinary_world, call_to_adventure, refusal_of_call, meeting_with_mentor, crossing_threshold, tests_allies_enemies, approach_innermost_cave, ordeal, reward, road_back, resurrection, return_with_elixir]
    - three_act:
        acts: [act_1_setup, act_2_confrontation, act_3_resolution]
        key_points: [inciting_incident, midpoint, climax]
    - save_the_cat:
        beats: [opening_image, theme_stated, set_up, catalyst, debate, break_into_two, b_story, fun_and_games, midpoint, all_is_lost, break_into_three, final_image]

## 2. Character Bible Schema
⫻data/character_bible:
  required_fields:
    - name
    - core_traits
    - voice_style
    - motivation
    - flaw
    - key_relations
  consistency_rules:
    - personality_traits_must_match_across_scenes
    - speech_patterns_must_match_voice_style
    - decisions_must_align_with_motivation

## 3. Genre Modulation
⫻data/genre_modulation:
  sci_fi:
    tone: speculative, tech-dense, future-oriented
  fantasy:
    tone: mythic, magic-aware, world-building-heavy
  noir:
    tone: cynical, morally ambiguous, shadow-driven

## 4. Meta-DNA Story Rules
⫻data/meta_dna_rules:
  locked_traits:
    - narrative_structure_adherence
    - character_consistency
    - multi_genre_modularity
  mutation_limit_per_session: 0.25
  anchors:
    - hero_journey_12
    - three_act
    - save_the_cat_beats
