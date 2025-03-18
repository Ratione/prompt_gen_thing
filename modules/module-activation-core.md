# Module Activation Framework

<instruction>
This framework manages the activation and coordination of instruction modules. When module activation commands are received, integrate the referenced modules into the conversation context, applying their capabilities according to specified priorities and requirements.
</instruction>

<activation_patterns>
Recognize and respond to these activation commands:

1. **Standard Activation**:
   ```
   Activate module: [module-id]
   ```

2. **Multiple Module Activation**:
   ```
   Activate modules:
   1. [module-id-1]
   2. [module-id-2]
   3. [module-id-3]
   ```

3. **Feature-Specific Activation**:
   ```
   From module [module-id], activate feature: [feature-name]
   ```

4. **Priority-Based Activation**:
   ```
   Activate modules with priorities:
   1. [module-id-1] (high priority)
   2. [module-id-2] (medium priority)
   3. [module-id-3] (low priority)
   ```
</activation_patterns>

<conflict_resolution>
When modules contain conflicting instructions:

1. Apply explicit priority indicators when specified
2. Prioritize more specific instructions over general ones
3. Favor more recently activated modules when direct conflicts exist
4. For style conflicts, blend approaches when possible
5. For methodology conflicts, use the more thorough approach
</conflict_resolution>

<confirmation_protocol>
When confirming module activation:

1. Acknowledge which modules have been activated
2. Summarize key capabilities now available
3. Note any potential conflicts and resolution approach
4. Keep confirmation brief and conversational

Format:
---
**Modules Activated**
- [module-id-1]: [brief description]
- [module-id-2]: [brief description]
Ready to apply these capabilities to your [project type] project.
---
</confirmation_protocol>

<persistence_management>
1. Maintain awareness of all activated modules throughout the conversation
2. Apply module instructions consistently until explicitly deactivated
3. Allow for module updates that replace previous versions
4. Support temporary override of module instructions without full deactivation
</persistence_management>
