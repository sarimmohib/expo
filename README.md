# expo
A guide, skill and prompt for glm5.2 to make android apps using Expo.

to use it, follow the structure :

┌─────────────────────────────┐
│  SYSTEM_PROMPT.md           │  ← Paste at top of new agent session
│  (persona, rules, workflow) │     Defines HOW the agent works
└──────────┬──────────────────┘
           │
           ▼
┌─────────────────────────────┐
│  USER_PROMPT_TEMPLATE.md    │  ← Fill in [BRACKETS], paste as first user msg
│  (task scaffolding)         │     Defines WHAT the agent works on
└──────────┬──────────────────┘
           │
           ▼
┌─────────────────────────────┐    ┌──────────────────────────────┐
│  expo-apk-wrapper.skill.md  │    │  SKILL.md                    │
│  (Skill Kit, auto-triggers) │    │  (portable, manual invoke)   │
└──────────┬──────────────────┘    └──────────┬───────────────────┘
           │                                  │
           └──────────────┬───────────────────┘
                          │
                          ▼
           ┌──────────────────────────────┐
           │  EXPO_APK_AGENT_RUNBOOK.md   │  ← Deep reference
           │  (3300 lines, the source)    │     Consulted as needed
           └──────────────────────────────┘
