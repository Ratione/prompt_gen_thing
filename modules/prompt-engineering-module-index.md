# Prompt Engineering Module Index

This index catalogs the complete set of prompt engineering modules created from the original comprehensive prompt. These modules can be activated individually or in combination to create optimized prompts for various purposes.

## Core Infrastructure Modules

| Module ID | Purpose | Key Capabilities |
|-----------|---------|------------------|
| module-activation-core | Manages module activation and integration | • Module activation commands<br>• Conflict resolution<br>• Persistence management |
| conversation-management-module | Manages conversation length and context | • Breakpoint identification<br>• Context summarization<br>• Token optimization |

## Prompt Engineering Process Modules

| Module ID | Purpose | Key Capabilities |
|-----------|---------|------------------|
| goal-exploration-module | Explores user objectives through strategic questioning | • Structured exploration questions<br>• Implementation approach<br>• Exploration sequence |
| prompt-evolution-module | Guides evaluation and refinement of prompts | • Effectiveness evaluation<br>• Use case adaptation<br>• Progressive refinement |
| deliverables-module | Defines comprehensive prompt engineering deliverables | • Required deliverable components<br>• Structured formats<br>• Quality standards |

## Technical Implementation Modules

| Module ID | Purpose | Key Capabilities |
|-----------|---------|------------------|
| extended-thinking-module | Activates Claude's deep analytical capabilities | • Activation techniques<br>• Structured reasoning patterns<br>• Implementation guidance |
| xml-structure-module | Implements Anthropic's XML structure recommendations | • XML components<br>• Structural patterns<br>• Optimization techniques |
| optimization-principles-module | Applies systematic optimization to prompts | • Efficiency principles<br>• Optimization techniques<br>• Implementation workflow |
| documentation-integration-module | Incorporates Anthropic documentation best practices | • Documentation section references<br>• Implementation approaches<br>• Reference patterns |
| multishot-prompting-module | Implements few-shot learning techniques | • Example design strategies<br>• Implementation patterns<br>• Optimization techniques |

## Activation Patterns

### Basic Module Activation

```
Activate module: [module-id]
```

Example:
```
Activate module: goal-exploration-module
```

### Multiple Module Activation

```
Activate modules:
1. [module-id-1]
2. [module-id-2]
3. [module-id-3]
```

Example:
```
Activate modules:
1. goal-exploration-module
2. extended-thinking-module
3. xml-structure-module
```

### Feature-Specific Activation

```
From module [module-id], activate feature: [feature-name]
```

Example:
```
From module extended-thinking-module, activate feature: structured_reasoning_patterns
```

### Priority-Based Activation

```
Activate modules with priorities:
1. [module-id-1] (high priority)
2. [module-id-2] (medium priority)
3. [module-id-3] (low priority)
```

Example:
```
Activate modules with priorities:
1. xml-structure-module (high priority)
2. optimization-principles-module (high priority)
3. documentation-integration-module (medium priority)
4. deliverables-module (low priority)
```

## Module Combinations for Different Scenarios

### Prompt Creation Workflow

For creating new prompts from scratch:
```
Activate modules:
1. goal-exploration-module
2. xml-structure-module
3. extended-thinking-module
4. optimization-principles-module
5. deliverables-module
```

### Prompt Optimization Workflow

For optimizing existing prompts:
```
Activate modules:
1. optimization-principles-module 
2. documentation-integration-module
3. prompt-evolution-module
```

### Long-Term Project Management

For managing extended prompt engineering projects:
```
Activate modules:
1. conversation-management-module
2. goal-exploration-module
3. prompt-evolution-module
4. deliverables-module
```

## Module Extension Process

To create new modules following this pattern:

1. Identify a distinct functional area of prompt engineering
2. Create a module with the following sections:
   - `<instruction>`: Core purpose and function
   - Feature-specific sections with descriptive XML tags
   - `<implementation_guidance>`: Practical application advice
3. Add the new module to this index
4. Document its integration points with existing modules