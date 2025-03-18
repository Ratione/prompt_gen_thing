# Extended Thinking Implementation Module

<instruction>
Design prompts that activate and optimize Claude's extended thinking capabilities for complex analytical tasks. Implement structured approaches that encourage thorough reasoning, consideration of alternatives, and systematic evaluation of information.
</instruction>

<activation_techniques>
Employ these techniques to activate extended thinking mode:

1. **Explicit Instruction**:
   Include "Use extended thinking mode for this analysis" at the beginning of critical prompts

2. **Structured Reasoning**:
   Implement `<reasoning_path>` tags to break complex problems into interconnected sub-questions

3. **Alternative Consideration**:
   Use `<alternatives>` tags to request explicit consideration of multiple approaches

4. **Evaluation Framework**:
   For evaluative tasks, structure as: criteria → evidence → analysis → conclusion

5. **Step-by-Step Directive**:
   Include the phrase "consider step by step" in complex reasoning prompts

6. **Thinking Space**:
   Create `<thinking>` tags for Claude to work through reasoning before delivering conclusions
</activation_techniques>

<structured_reasoning_patterns>
Implement these patterns for complex problems:

1. **Decomposition Pattern**:
   Break large problems into defined sub-problems with clear relationships

2. **Criteria-Based Evaluation**:
   Establish explicit evaluation criteria before analyzing options

3. **Counter-Argument Consideration**:
   Explicitly request examination of opposing viewpoints and limitations

4. **Multi-Perspective Analysis**:
   Analyze issues from different disciplinary or stakeholder perspectives

5. **Confidence Assessment**:
   Request explicit assessment of confidence levels for different conclusions

6. **Decision Matrix Approach**:
   Create structured comparison of options across multiple dimensions
</structured_reasoning_patterns>

<example_implementations>
Example implementation for a complex analysis task:

```
<instruction>
Use extended thinking mode to analyze the potential impacts of this policy change.
</instruction>

<reasoning_path>
1. What are the stated objectives of this policy?
2. Who are the key stakeholders affected?
3. What direct effects can be anticipated in the short term?
4. What indirect or second-order effects might emerge?
5. What potential unintended consequences should be considered?
6. How do historical analogues inform our understanding?
7. What monitoring metrics would indicate success or failure?
</reasoning_path>

<alternatives>
Consider at least three alternative approaches to achieving the same objectives.
</alternatives>

<evaluation_framework>
Evaluate each approach using these criteria:
- Effectiveness in achieving stated objectives
- Resource requirements and efficiency
- Distributional impacts across stakeholder groups
- Robustness to uncertainty and changing conditions
- Implementation complexity and barriers
</evaluation_framework>
```
</example_implementations>

<implementation_guidance>
When implementing extended thinking:

1. Match reasoning structure to problem type (analytical, evaluative, creative, etc.)
2. Provide sufficient context but avoid overwhelming with irrelevant details
3. Create space for exploration without excessive constraints
4. Consider time and complexity tradeoffs for different approaches
5. Design prompts that encourage both depth and breadth of analysis
6. Balance structured guidance with room for novel insights
</implementation_guidance>
