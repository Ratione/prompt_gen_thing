# Anthropic XML Structure Module

<instruction>
Implement Anthropic's recommended XML structure for optimal Claude performance. Design prompts with clear, well-organized sections that maximize Claude's ability to understand requirements and generate appropriate responses.
</instruction>

<xml_components>
Implement these core XML components in prompt design:

1. **`<instruction>`**:
   - Clear, concise directives for immediate task execution
   - Action-oriented language with specific expected outputs
   - Prioritized requirements when multiple objectives exist

2. **`<context>`**:
   - Essential background information directly relevant to the task
   - Historical or situational details needed for appropriate responses
   - Scope limitations and domain-specific context

3. **`<examples>`**:
   - Structured demonstrations following Anthropic's few-shot learning format
   - Clear input/output pairs showing expected patterns
   - Examples covering edge cases or complex scenarios

4. **`<constraints>`**:
   - Explicit boundaries and limitations for Claude's response
   - Prohibited content, approaches, or assumptions
   - Format restrictions or requirements

5. **`<format>`**:
   - Precise specification of response structure
   - Templates or patterns for output consistency
   - Sections, headings, or organization requirements

6. **`<evaluation>`**:
   - Criteria for Claude to self-assess response quality
   - Quality standards or benchmarks
   - Self-verification steps before responding
</xml_components>

<structural_patterns>
Implement these structural patterns for different prompt types:

1. **Sequential Process**:
   ```
   <instruction>...</instruction>
   <context>...</context>
   <process>
     <step1>...</step1>
     <step2>...</step2>
     <step3>...</step3>
   </process>
   <output_format>...</output_format>
   ```

2. **Analytical Framework**:
   ```
   <instruction>...</instruction>
   <context>...</context>
   <analysis_framework>
     <criteria>...</criteria>
     <evidence>...</evidence>
     <evaluation>...</evaluation>
     <conclusion>...</conclusion>
   </analysis_framework>
   ```

3. **Creative Generation**:
   ```
   <instruction>...</instruction>
   <parameters>
     <style>...</style>
     <tone>...</tone>
     <audience>...</audience>
     <constraints>...</constraints>
   </parameters>
   <examples>...</examples>
   ```
</structural_patterns>

<implementation_guidelines>
When implementing XML structure:

1. Use descriptive, semantic tag names that reflect content purpose
2. Maintain consistent indentation for nested structures
3. Separate conceptually distinct information into different tags
4. Order tags in a logical sequence that builds understanding
5. Balance comprehensive structure with prompt conciseness
6. Use nested tags for hierarchical information
7. Close all tags properly to maintain structural integrity
</implementation_guidelines>

<optimization_techniques>
Optimize XML structure for Claude with these techniques:

1. Place most critical instructions at the beginning
2. Group related information within semantic tag boundaries
3. Use consistent tag naming conventions throughout prompts
4. Separate examples clearly from instructions
5. Balance detail with conciseness in each section
6. Create clear visual structure with spacing and formatting
7. Use enum or list structures for multiple items rather than long paragraphs
</optimization_techniques>
