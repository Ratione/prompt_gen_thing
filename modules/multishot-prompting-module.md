# Multishot Prompting Module

<instruction>
Implement Anthropic's multishot prompting techniques to improve prompt consistency, clarity, and effectiveness. Design example sets that establish clear patterns for Claude to follow, leveraging few-shot learning capabilities while maintaining efficiency.
</instruction>

<multishot_principles>
Apply these core principles when designing multishot examples:

1. **Pattern Clarity**:
   - Establish clear, consistent patterns across all examples
   - Maintain identical formatting and structure
   - Use explicit separators between inputs and outputs

2. **Strategic Coverage**:
   - Include 2-5 examples for optimal learning
   - Cover the range of expected variations
   - Represent both typical cases and edge cases

3. **Progressive Complexity**:
   - Order examples from simpler to more complex when possible
   - Demonstrate handling of special conditions or exceptions
   - Show different but related patterns when appropriate

4. **Contextual Relevance**:
   - Match examples to the user's domain and vocabulary
   - Use realistic content that reflects actual usage
   - Balance generic applicability with domain specificity

5. **Format Consistency**:
   - Use identical formatting across all examples
   - Maintain consistent labeling and structure
   - Ensure clear visual distinction between input and output
</multishot_principles>

<implementation_patterns>
Implement these specific patterns for multishot prompting:

1. **Standard Input-Output Pattern**:
   ```
   Input: [example input 1]
   Output: [example output 1]
   
   Input: [example input 2]
   Output: [example output 2]
   
   Input: [example input 3]
   Output: [example output 3]
   
   Input: [actual task input]
   Output: 
   ```

2. **Conversation Pattern**:
   ```
   User: [example user message 1]
   Assistant: [example assistant response 1]
   
   User: [example user message 2]
   Assistant: [example assistant response 2]
   
   User: [actual user message]
   Assistant:
   ```

3. **XML-Tagged Pattern**:
   ```
   <example>
     <input>[example input 1]</input>
     <output>[example output 1]</output>
   </example>
   
   <example>
     <input>[example input 2]</input>
     <output>[example output 2]</output>
   </example>
   
   <input>[actual task input]</input>
   <output>
   ```

4. **Implicit Pattern**:
   ```
   [Description of task]
   
   Example 1: [input] → [output]
   Example 2: [input] → [output]
   Example 3: [input] → [output]
   
   Now: [input] →
   ```
</implementation_patterns>

<example_design_strategies>
Use these strategies when designing effective examples:

1. **Diversity with Consistency**:
   Create examples that vary in content but follow identical patterns

2. **Edge Case Coverage**:
   Include examples that demonstrate handling of unusual or boundary conditions

3. **Progression Planning**:
   Order examples to build understanding from basic to complex cases

4. **Pattern Reinforcement**:
   Repeat key patterns across multiple examples to strengthen learning

5. **Implicit Rule Demonstration**:
   Show rather than tell the rules governing the transformation

6. **Balanced Representation**:
   Ensure examples cover the full range of expected variations
</example_design_strategies>

<optimization_techniques>
Apply these techniques to optimize multishot prompts:

1. **Example Minimization**:
   Use the minimum number of examples needed to establish the pattern clearly

2. **Token Efficiency**:
   Create concise examples that demonstrate patterns without unnecessary content

3. **Pattern Emphasis**:
   Highlight the most important aspects of the pattern for learning

4. **Essential Variation**:
   Include only variations that demonstrate important distinctions

5. **Content Compression**:
   Use representative shortened content when full content isn't necessary

6. **Staged Examples**:
   In complex cases, introduce examples in stages to build understanding
</optimization_techniques>

<application_guidance>
Apply multishot prompting in these scenarios:

1. For tasks requiring specific output formats or structures
2. When consistency across multiple responses is critical
3. For complex transformations with implicit rules
4. When teaching Claude new domain-specific patterns
5. For tasks involving specialized notation or formatting
6. When previous zero-shot attempts produced inconsistent results
</application_guidance>
