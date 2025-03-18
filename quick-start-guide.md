# Modular Prompt Engineering: Quick Start Guide

This guide provides the essential steps to immediately start using the modular prompt engineering system with Claude. For more detailed information, refer to the comprehensive implementation guide.

## 10-Minute Setup

### Step 1: Initialize a New Project

Start a new conversation in Claude and paste this message:

```
I'd like to set up a modular prompt engineering system for our work together. Please acknowledge once I've shared the core modules, and then we'll activate specific modules for our project.
```

### Step 2: Add Core Infrastructure

Copy and paste these essential modules (you can get these from the artifacts in this conversation):

1. `module-activation-core`
2. `conversation-management-module`

### Step 3: Add Task-Specific Modules

Based on your immediate needs, add the most relevant modules. For most projects, these are recommended:

1. `goal-exploration-module`
2. `xml-structure-module`
3. One or two additional modules specific to your current task

### Step 4: Activate Modules

Add this activation command:

```
Activate modules:
1. goal-exploration-module
2. xml-structure-module
3. [any other modules you added]

Now let's begin working on [brief description of your prompt engineering task].
```

## Common Module Combinations

### For New Prompt Creation

```
Activate modules:
1. goal-exploration-module
2. xml-structure-module
3. extended-thinking-module
4. optimization-principles-module
```

### For Prompt Optimization

```
Activate modules:
1. optimization-principles-module
2. documentation-integration-module
3. prompt-evolution-module
```

### For Educational Prompt Development

```
Activate modules:
1. goal-exploration-module
2. xml-structure-module
3. deliverables-module
```

## What to Paste in Anthropic's "Prompt" Section

When using Claude's desktop program or web interface where there's a dedicated "Prompt" section, use this streamlined approach:

```
You are an Advanced Prompt Engineering Specialist using a modular approach to prompt design. You'll be receiving modular instruction components that should be integrated into your capabilities without requiring repetition.

Key capabilities you should maintain throughout our conversation:
1. Module activation and integration
2. Conversation length and context management
3. Strategic questioning for goal exploration
4. XML structure implementation
5. Documentation integration
6. Optimization for token efficiency

When I activate specific modules, incorporate their capabilities into your approach without needing to repeat back the module contents. Acknowledge activation with a brief confirmation only.

Let's begin our prompt engineering project focused on [your specific focus area].
```

This minimal prompt establishes the framework while conserving tokens, allowing you to add specific modules as needed during the conversation.

## Quick Reference: Module Activation Commands

### Basic Activation
```
Activate module: [module-id]
```

### Multiple Module Activation
```
Activate modules:
1. [module-id-1]
2. [module-id-2]
3. [module-id-3]
```

### Feature-Specific Activation
```
From module [module-id], activate feature: [feature-name]
```

### Priority-Based Activation
```
Activate modules with priorities:
1. [module-id-1] (high priority)
2. [module-id-2] (medium priority)
3. [module-id-3] (low priority)
```

## Tips for Efficient Usage

1. **Start minimal**: Begin with only the modules you immediately need
2. **Use conversation breakpoints**: Create new conversations at logical transition points
3. **Save modules externally**: Keep a copy of your modules in your own notes system
4. **Build gradually**: Add modules one by one as your needs evolve
5. **Reference, don't repeat**: Use artifact references rather than pasting content multiple times

## Next Steps

After this quick start:
1. Explore creating custom modules for your specific needs
2. Experiment with different module combinations 
3. Develop a personal library of tested modules
4. Review the comprehensive implementation guide for advanced techniques
