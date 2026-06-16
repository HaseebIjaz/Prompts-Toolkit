# Structured Prompt / Workflow Schema

## 1. Goal Definition

- objective: what must be achieved
- success_criteria: how you know it's done
- primary_output: artifact type (doc, plan, code, design, etc.)
- audience: who the output is for
- priority: what matters most (speed, accuracy, depth, creativity)
- scope: what is included / excluded
- problem_statement: raw description of the problem

## 2. Context Provisioning

- background_info: relevant domain info
- current_state: what exists now
- constraints_from_environment: external limitations (tech, business, real-world)
- assumptions: what is assumed true
- references: docs, links, prior knowledge
- domain: field/category (e.g., TS, game design)
- user_preferences: style, tone, approach preferences

## 3. Constraint Definition

- hard_constraints: non-negotiable rules
- soft_constraints: flexible guidelines
- format_constraints: structure requirements
- tech_constraints: tools, frameworks, languages allowed
- resource_limits: time, compute, budget
- quality_constraints: performance thresholds
- prohibited_elements: what must not appear

## 4. Instruction Design

- role: persona or expert model
- task_definition: what model must do
- behavior_rules: how it should behave
- response_format: output structure
- reasoning_style: analytical, creative, stepwise, etc.
- tone: formal, concise, exploratory
- depth_level: shallow / medium / deep

## 5. Example Conditioning

- examples: input → output pairs
- negative_examples: what NOT to do
- pattern_templates: reusable structures
- edge_cases: tricky scenarios
- variation_samples: diversity examples

## 6. Planning

- task_decomposition: breakdown of steps
- dependencies: what depends on what
- execution_order: sequence of steps
- risk_points: where things can fail
- alternative_paths: fallback strategies
- milestones: intermediate checkpoints

## 7. Initial Generation

- initial_output: first full draft/result
- coverage_map: what parts are addressed
- confidence_level: how strong the output is
- uncertainties: unknown or weak areas
- assumptions_used: what was assumed during generation

## 8. Exploration

- alternatives: different approaches
- hypotheses: possible interpretations/solutions
- open_questions: unresolved areas
- variations: expanded versions
- search_space: conceptual range being explored

## 9. Iteration

- revision_cycle: iteration number
- changes_applied: what was modified
- diff_from_previous: delta explanation
- improvement_target: what is being improved
- regressions_checked: what must not break

## 10. Feedback

- feedback_source: user / system / self
- feedback_type: correction / suggestion / approval
- issues: problems identified
- strengths: what is working
- priority_fixes: what to fix first
- clarifications_needed: missing info

## 11. Tool Use / Retrieval

- tool_name: which tool is used
- input_query: what was asked
- retrieved_data: returned info
- relevance_score: usefulness of data
- integration_plan: how it will be used

## 12. Reflection / Self-Critique

- self_assessment: internal evaluation
- logical_gaps: reasoning issues
- consistency_check: internal contradictions
- quality_score: subjective score
- improvement_suggestions: how to improve

## 13. Evaluation

- evaluation_criteria: what is being measured
- scorecard: structured scoring
- pass_fail: binary outcome per criterion
- alignment_with_goal: match to objective
- risk_assessment: possible failure impact

## 14. Judgment

- decisions: what is accepted/rejected
- selection_reasoning: why decisions were made
- prioritization: ranked outputs or options
- tradeoffs: what was sacrificed
- final_choice: selected direction

## 15. Convergence

- final_direction: unified solution path
- merged_insights: combined ideas
- resolved_conflicts: contradictions fixed
- final_structure: final architecture/layout
- stability_level: confidence in final form

## 16. Finalization

- final_output: deliverable
- formatting_applied: formatting rules used
- polish_level: refinement status
- completeness_check: coverage confirmation
- delivery_mode: how it is presented

## 17. Stopping

- stopping_reason: why we stop now
- completion_status: complete / partial / bounded
- remaining_unknowns: what is left unresolved
- future_work: optional next steps
- final_confidence: confidence in sufficiency
