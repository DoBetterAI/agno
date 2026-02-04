# Repository Tree (depth=4)

├── .github
│   ├── ISSUE_TEMPLATE
│   │   ├── bug-report.yml
│   │   ├── config.yml
│   │   └── feature-request.yml
│   ├── workflows
│   │   ├── claude.yml
│   │   ├── performance.yml
│   │   ├── pr-lint.yml
│   │   ├── release.yml
│   │   ├── stale-issues.yml
│   │   ├── test.yml
│   │   └── test_on_release.yml
│   └── pull_request_template.md
├── cookbook
│   ├── 00_quickstart
│   │   ├── .gitignore
│   │   ├── __init__.py
│   │   ├── agent_search_over_knowledge.py
│   │   ├── agent_with_guardrails.py
│   │   ├── agent_with_memory.py
│   │   ├── agent_with_state_management.py
│   │   ├── agent_with_storage.py
│   │   ├── agent_with_structured_output.py
│   │   ├── agent_with_tools.py
│   │   ├── agent_with_typed_input_output.py
│   │   ├── CLAUDE.md
│   │   ├── config.yaml
│   │   ├── custom_tool_for_self_learning.py
│   │   ├── generate_requirements.sh
│   │   ├── human_in_the_loop.py
│   │   ├── multi_agent_team.py
│   │   ├── README.md
│   │   ├── requirements.in
│   │   ├── requirements.txt
│   │   ├── run.py
│   │   ├── sequential_workflow.py
│   │   └── TEST_LOG.md
│   ├── 01_showcase
│   │   ├── 01_agents
│   │   │   ├── document_summarizer
│   │   │   │   ├── documents
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── tools
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── inbox_agent
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── invoice_analyst
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── tools
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── knowledge_agent
│   │   │   │   ├── examples
│   │   │   │   ├── knowledge
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── linear_agent
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── meeting_tasks_agent
│   │   │   │   ├── examples
│   │   │   │   ├── meetings
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── recipe_agent
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── research_agent
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── social_media_analyst
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── startup_analyst
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── schemas.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── text_to_sql
│   │   │   │   ├── examples
│   │   │   │   ├── knowledge
│   │   │   │   ├── scripts
│   │   │   │   ├── tools
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   ├── semantic_model.py
│   │   │   │   └── TEST_LOG.md
│   │   │   ├── translation_agent
│   │   │   │   ├── examples
│   │   │   │   ├── scripts
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.in
│   │   │   │   └── TEST_LOG.md
│   │   │   └── __init__.py
│   │   ├── 02_teams
│   │   │   ├── __init__.py
│   │   │   ├── ai_customer_support_team.py
│   │   │   ├── autonomous_startup_team.py
│   │   │   ├── db.py
│   │   │   ├── news_agency_team.py
│   │   │   ├── skyplanner_mcp_team.py
│   │   │   ├── TEST_LOG.md
│   │   │   └── tic_tac_toe_team.py
│   │   ├── 03_workflows
│   │   │   ├── __init__.py
│   │   │   ├── db.py
│   │   │   ├── employee_recruiter_async_stream.py
│   │   │   ├── investment_report_generator.py
│   │   │   ├── research_workflow.py
│   │   │   ├── startup_idea_validator.py
│   │   │   └── TEST_LOG.md
│   │   ├── 04_gemini
│   │   │   ├── agents
│   │   │   │   ├── __init__.py
│   │   │   │   ├── creative_studio_agent.py
│   │   │   │   ├── db.py
│   │   │   │   ├── pal_agent.py
│   │   │   │   ├── product_comparison_agent.py
│   │   │   │   ├── self_learning_agent.py
│   │   │   │   └── self_learning_research_agent.py
│   │   │   ├── assets
│   │   │   │   ├── agentos_1.png
│   │   │   │   ├── agentos_2.png
│   │   │   │   ├── agentos_3.png
│   │   │   │   └── agentos_4.png
│   │   │   ├── __init__.py
│   │   │   ├── config.yaml
│   │   │   ├── db.py
│   │   │   ├── generate_requirements.sh
│   │   │   ├── README.md
│   │   │   ├── requirements.in
│   │   │   ├── requirements.txt
│   │   │   └── run.py
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 02_agents
│   │   ├── agentic_search
│   │   │   ├── lightrag
│   │   │   │   ├── agentic_rag_with_lightrag.py
│   │   │   │   └── readme.md
│   │   │   ├── __init__.py
│   │   │   ├── agentic_rag.py
│   │   │   ├── agentic_rag_infinity_reranker.py
│   │   │   └── agentic_rag_with_reasoning.py
│   │   ├── async
│   │   │   ├── __init__.py
│   │   │   ├── basic.py
│   │   │   ├── concurrent_tool_calls.py
│   │   │   ├── data_analyst.py
│   │   │   ├── delay.py
│   │   │   ├── gather_agents.py
│   │   │   ├── reasoning.py
│   │   │   ├── streaming.py
│   │   │   ├── structured_output.py
│   │   │   └── tool_use.py
│   │   ├── caching
│   │   │   ├── __init__.py
│   │   │   ├── async_cache_model_response.py
│   │   │   ├── async_cache_model_response_stream.py
│   │   │   ├── cache_model_response.py
│   │   │   └── cache_model_response_stream.py
│   │   ├── context_compression
│   │   │   ├── async_tool_call_compression.py
│   │   │   ├── compression_events.py
│   │   │   ├── token_based_tool_call_compression.py
│   │   │   ├── tool_call_compression.py
│   │   │   └── tool_call_compression_with_manager.py
│   │   ├── context_management
│   │   │   ├── __init__.py
│   │   │   ├── datetime_instructions.py
│   │   │   ├── dynamic_instructions.py
│   │   │   ├── few_shot_learning.py
│   │   │   ├── filter_tool_calls_from_history.py
│   │   │   ├── instruction_tags.py
│   │   │   ├── instructions_via_function.py
│   │   │   ├── introduction.py
│   │   │   └── location_instructions.py
│   │   ├── culture
│   │   │   ├── 01_create_cultural_knowledge.py
│   │   │   ├── 02_use_cultural_knowledge_in_agent.py
│   │   │   ├── 03_automatic_cultural_management.py
│   │   │   ├── 04_manually_add_culture.py
│   │   │   ├── 05_test_agent_with_culture.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── custom_logging
│   │   │   ├── __init__.py
│   │   │   ├── custom_logging.py
│   │   │   ├── custom_logging_advanced.py
│   │   │   └── log_to_file.py
│   │   ├── dependencies
│   │   │   ├── __init__.py
│   │   │   ├── access_dependencies_in_tool.py
│   │   │   ├── add_dependencies_on_run.py
│   │   │   ├── add_dependencies_to_context.py
│   │   │   ├── dependencies_functions.py
│   │   │   ├── README.md
│   │   │   └── reference_dependencies.py
│   │   ├── events
│   │   │   ├── __init__.py
│   │   │   ├── basic_agent_events.py
│   │   │   └── reasoning_agent_events.py
│   │   ├── guardrails
│   │   │   ├── openai_moderation.py
│   │   │   ├── pii_detection.py
│   │   │   └── prompt_injection.py
│   │   ├── hooks
│   │   │   ├── input_transformation_pre_hook.py
│   │   │   ├── input_validation_pre_hook.py
│   │   │   ├── output_stream_hook_send_notification.py
│   │   │   ├── output_transformation_post_hook.py
│   │   │   ├── output_validation_post_hook.py
│   │   │   ├── session_state_post_hook.py
│   │   │   └── session_state_pre_hook.py
│   │   ├── human_in_the_loop
│   │   │   ├── __init__.py
│   │   │   ├── agentic_user_input.py
│   │   │   ├── confirmation_required.py
│   │   │   ├── confirmation_required_async.py
│   │   │   ├── confirmation_required_mcp_toolkit.py
│   │   │   ├── confirmation_required_mixed_tools.py
│   │   │   ├── confirmation_required_multiple_tools.py
│   │   │   ├── confirmation_required_stream.py
│   │   │   ├── confirmation_required_stream_async.py
│   │   │   ├── confirmation_required_toolkit.py
│   │   │   ├── confirmation_required_with_history.py
│   │   │   ├── confirmation_required_with_run_id.py
│   │   │   ├── external_tool_execution.py
│   │   │   ├── external_tool_execution_async.py
│   │   │   ├── external_tool_execution_async_responses.py
│   │   │   ├── external_tool_execution_stream.py
│   │   │   ├── external_tool_execution_stream_async.py
│   │   │   ├── external_tool_execution_toolkit.py
│   │   │   ├── user_input_required.py
│   │   │   ├── user_input_required_all_fields.py
│   │   │   ├── user_input_required_async.py
│   │   │   ├── user_input_required_stream.py
│   │   │   └── user_input_required_stream_async.py
│   │   ├── input_and_output
│   │   │   ├── __init__.py
│   │   │   ├── input_as_dict.py
│   │   │   ├── input_as_list.py
│   │   │   ├── input_as_message.py
│   │   │   ├── input_as_messages_list.py
│   │   │   ├── input_schema_on_agent.py
│   │   │   ├── input_schema_on_agent_as_typed_dict.py
│   │   │   ├── instructions.py
│   │   │   ├── json_schema_output.py
│   │   │   ├── output_model.py
│   │   │   ├── output_schema_override.py
│   │   │   ├── parser_model.py
│   │   │   ├── parser_model_ollama.py
│   │   │   ├── parser_model_stream.py
│   │   │   ├── response_as_variable.py
│   │   │   ├── structured_input.py
│   │   │   └── structured_input_output_with_parser_model.py
│   │   ├── multimodal
│   │   │   ├── .gitignore
│   │   │   ├── 01_media_input_for_tool.py
│   │   │   ├── 02_media_input_to_agent_and_tool.py
│   │   │   ├── __init__.py
│   │   │   ├── agent_same_run_image_analysis.py
│   │   │   ├── agent_using_multimodal_tool_response_in_runs.py
│   │   │   ├── audio_input_output.py
│   │   │   ├── audio_multi_turn.py
│   │   │   ├── audio_sentiment_analysis.py
│   │   │   ├── audio_streaming.py
│   │   │   ├── audio_to_text.py
│   │   │   ├── generate_image_with_intermediate_steps.py
│   │   │   ├── generate_video_using_models_lab.py
│   │   │   ├── generate_video_using_replicate.py
│   │   │   ├── image_input_high_fidelity.py
│   │   │   ├── image_input_multi-turn.py
│   │   │   ├── image_to_audio.py
│   │   │   ├── image_to_image_agent.py
│   │   │   ├── image_to_structured_output.py
│   │   │   ├── image_to_text.py
│   │   │   ├── video_caption_agent.py
│   │   │   └── video_to_shorts.py
│   │   ├── other
│   │   │   ├── __init__.py
│   │   │   ├── agent_extra_metrics.py
│   │   │   ├── agent_metrics.py
│   │   │   ├── agent_model_string.py
│   │   │   ├── agent_retries.py
│   │   │   ├── agent_run_metadata.py
│   │   │   ├── cancel_a_run.py
│   │   │   ├── cancel_a_run_async_with_redis.py
│   │   │   ├── cancel_a_run_with_redis.py
│   │   │   ├── debug.py
│   │   │   ├── debug_level.py
│   │   │   ├── intermediate_steps.py
│   │   │   ├── run_response_events.py
│   │   │   ├── scenario_testing.py
│   │   │   └── tool_call_limit.py
│   │   ├── rag
│   │   │   ├── __init__.py
│   │   │   ├── agentic_rag_lancedb.py
│   │   │   ├── agentic_rag_pgvector.py
│   │   │   ├── agentic_rag_with_reranking.py
│   │   │   ├── local_rag_langchain_qdrant.py
│   │   │   ├── rag_sentence_transformer.py
│   │   │   ├── rag_with_lance_db_and_sqlite.py
│   │   │   ├── README.md
│   │   │   ├── traditional_rag_lancedb.py
│   │   │   └── traditional_rag_pgvector.py
│   │   ├── session
│   │   │   ├── 01_persistent_session.py
│   │   │   ├── 02_persistent_session_history.py
│   │   │   ├── 03_session_summary.py
│   │   │   ├── 04_session_summary_references.py
│   │   │   ├── 05_chat_history.py
│   │   │   ├── 06_rename_session.py
│   │   │   ├── 07_in_memory_db.py
│   │   │   ├── 08_cache_session.py
│   │   │   ├── 09_disable_storing_history_messages.py
│   │   │   ├── 10_disable_storing_tool_messages.py
│   │   │   ├── 11_custom_session_summary_instructions.py
│   │   │   ├── 12_async_session_summary.py
│   │   │   ├── 13_chat_history_num_messages.py
│   │   │   └── __init__.py
│   │   ├── skills
│   │   │   ├── sample_skills
│   │   │   │   ├── code-review
│   │   │   │   └── git-workflow
│   │   │   ├── __init__.py
│   │   │   ├── basic_skills.py
│   │   │   └── README.md
│   │   ├── state
│   │   │   ├── __init__.py
│   │   │   ├── agentic_session_state.py
│   │   │   ├── change_state_on_run.py
│   │   │   ├── dynamic_session_state.py
│   │   │   ├── last_n_session_messages.py
│   │   │   ├── manual_session_state_update.py
│   │   │   ├── overwrite_stored_session_state.py
│   │   │   ├── session_state_advanced.py
│   │   │   ├── session_state_basic.py
│   │   │   ├── session_state_in_context.py
│   │   │   ├── session_state_in_event.py
│   │   │   ├── session_state_in_instructions.py
│   │   │   └── session_state_multiple_users.py
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 03_agents
│   │   └── human_in_the_loop
│   │       └── external_tool_execution_silent.py
│   ├── 03_teams
│   │   ├── async_flows
│   │   │   ├── 01_async_coordination_team.py
│   │   │   ├── 02_async_delegate_to_all_members.py
│   │   │   ├── 03_async_respond_directly.py
│   │   │   ├── 04_concurrent_member_agents.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── basic_flows
│   │   │   ├── caching
│   │   │   │   └── cache_team_response.py
│   │   │   ├── 01_basic_coordination.py
│   │   │   ├── 02_respond_directly_router_team.py
│   │   │   ├── 03_delegate_to_all_members_cooperation.py
│   │   │   ├── 04_respond_directly_with_history.py
│   │   │   ├── 05_team_history.py
│   │   │   ├── 06_history_of_members.py
│   │   │   ├── 07_share_member_interactions.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── context_compression
│   │   │   ├── async_tool_call_compression.py
│   │   │   ├── tool_call_compression.py
│   │   │   └── tool_call_compression_with_manager.py
│   │   ├── context_management
│   │   │   ├── filter_tool_calls_from_history.py
│   │   │   └── introduction.py
│   │   ├── dependencies
│   │   │   ├── __init__.py
│   │   │   ├── access_dependencies_in_tool.py
│   │   │   ├── add_dependencies_on_run.py
│   │   │   ├── add_dependencies_to_context.py
│   │   │   ├── add_dependencies_to_member_context.py
│   │   │   ├── README.md
│   │   │   └── reference_dependencies.py
│   │   ├── distributed_rag
│   │   │   ├── 01_distributed_rag_pgvector.py
│   │   │   ├── 02_distributed_rag_lancedb.py
│   │   │   ├── 03_distributed_rag_with_reranking.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── guardrails
│   │   │   ├── __init__.py
│   │   │   ├── openai_moderation.py
│   │   │   ├── pii_detection.py
│   │   │   └── prompt_injection.py
│   │   ├── hooks
│   │   │   ├── __init__.py
│   │   │   ├── input_transformation_pre_hook.py
│   │   │   ├── input_validation_pre_hook.py
│   │   │   ├── output_stream_hook_send_notification.py
│   │   │   ├── output_transformation_post_hook.py
│   │   │   └── output_validation_post_hook.py
│   │   ├── knowledge
│   │   │   ├── 01_team_with_knowledge.py
│   │   │   ├── 02_team_with_knowledge_filters.py
│   │   │   ├── 03_team_with_agentic_knowledge_filters.py
│   │   │   ├── 04_team_with_custom_retriever_dependencies.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── memory
│   │   │   ├── 01_team_with_memory_manager.py
│   │   │   ├── 02_team_with_agentic_memory.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── metrics
│   │   │   ├── 01_team_metrics.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── multimodal
│   │   │   ├── __init__.py
│   │   │   ├── audio_sentiment_analysis.py
│   │   │   ├── audio_to_text.py
│   │   │   ├── generate_image_with_team.py
│   │   │   ├── image_to_image_transformation.py
│   │   │   ├── image_to_structured_output.py
│   │   │   ├── image_to_text.py
│   │   │   ├── media_input_for_tool.py
│   │   │   ├── README.md
│   │   │   └── video_caption_generation.py
│   │   ├── other
│   │   │   ├── __init__.py
│   │   │   ├── few_shot_learning.py
│   │   │   ├── input_as_dict.py
│   │   │   ├── input_as_list.py
│   │   │   ├── input_as_messages_list.py
│   │   │   ├── README.md
│   │   │   ├── response_as_variable.py
│   │   │   ├── run_as_cli.py
│   │   │   ├── team_cancel_a_run.py
│   │   │   ├── team_model_inheritance.py
│   │   │   ├── team_model_string.py
│   │   │   └── team_retries.py
│   │   ├── reasoning
│   │   │   ├── 01_reasoning_multi_purpose_team.py
│   │   │   ├── 02_async_multi_purpose_reasoning_team.py
│   │   │   ├── __init__.py
│   │   │   ├── medical_history.txt
│   │   │   └── README.md
│   │   ├── search_coordination
│   │   │   ├── 01_coordinated_agentic_rag.py
│   │   │   ├── 02_coordinated_reasoning_rag.py
│   │   │   ├── 03_distributed_infinity_search.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── session
│   │   │   ├── 01_persistent_session.py
│   │   │   ├── 02_persistent_session_history.py
│   │   │   ├── 03_session_summary.py
│   │   │   ├── 04_session_summary_references.py
│   │   │   ├── 05_chat_history.py
│   │   │   ├── 06_rename_session.py
│   │   │   ├── 07_in_memory_db.py
│   │   │   ├── 08_cache_session.py
│   │   │   ├── 09_history_num_messages.py
│   │   │   ├── 09_share_session_with_agent.py
│   │   │   ├── 10_async_session_summary.py
│   │   │   ├── 11_search_session_history.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── state
│   │   │   ├── __init__.py
│   │   │   ├── agentic_session_state.py
│   │   │   ├── change_state_on_run.py
│   │   │   ├── overwrite_stored_session_state.py
│   │   │   ├── pass_state_to_members.py
│   │   │   ├── README.md
│   │   │   ├── share_member_interactions.py
│   │   │   └── team_with_nested_shared_state.py
│   │   ├── streaming
│   │   │   ├── 01_team_streaming.py
│   │   │   ├── 02_events.py
│   │   │   ├── 03_async_team_streaming.py
│   │   │   ├── 04_async_team_events.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── structured_input_output
│   │   │   ├── 00_pydantic_model_output.py
│   │   │   ├── 01_pydantic_model_as_input.py
│   │   │   ├── 02_team_with_parser_model.py
│   │   │   ├── 03_team_with_output_model.py
│   │   │   ├── 04_structured_output_streaming.py
│   │   │   ├── 05_async_structured_output_streaming.py
│   │   │   ├── 06_input_schema_on_team.py
│   │   │   ├── 07_output_schema_override.py
│   │   │   ├── 08_json_schema_output.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── tools
│   │   │   ├── 01_team_with_custom_tools.py
│   │   │   ├── 02_team_with_tool_hooks.py
│   │   │   ├── 03_async_team_with_tools.py
│   │   │   ├── 04_tool_hooks_for_members.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 04_workflows
│   │   ├── _01_basic_workflows
│   │   │   ├── _01_sequence_of_steps
│   │   │   │   ├── async
│   │   │   │   ├── sync
│   │   │   │   └── __init__.py
│   │   │   ├── _02_step_with_function
│   │   │   │   ├── async
│   │   │   │   ├── sync
│   │   │   │   └── __init__.py
│   │   │   ├── _03_function_instead_of_steps
│   │   │   │   ├── async
│   │   │   │   ├── sync
│   │   │   │   └── __init__.py
│   │   │   └── __init__.py
│   │   ├── _02_workflows_conditional_execution
│   │   │   ├── async
│   │   │   │   ├── __init__.py
│   │   │   │   ├── condition_and_parallel_steps.py
│   │   │   │   ├── condition_and_parallel_steps_stream.py
│   │   │   │   ├── condition_steps_workflow_stream.py
│   │   │   │   ├── condition_with_else_steps.py
│   │   │   │   └── condition_with_list_of_steps.py
│   │   │   ├── sync
│   │   │   │   ├── __init__.py
│   │   │   │   ├── condition_and_parallel_steps.py
│   │   │   │   ├── condition_and_parallel_steps_stream.py
│   │   │   │   ├── condition_steps_workflow_stream.py
│   │   │   │   ├── condition_with_else_steps.py
│   │   │   │   └── condition_with_list_of_steps.py
│   │   │   └── __init__.py
│   │   ├── _03_workflows_loop_execution
│   │   │   ├── async
│   │   │   │   ├── __init__.py
│   │   │   │   ├── loop_steps_workflow.py
│   │   │   │   ├── loop_steps_workflow_stream.py
│   │   │   │   └── loop_with_parallel_steps_stream.py
│   │   │   ├── sync
│   │   │   │   ├── __init__.py
│   │   │   │   ├── loop_steps_workflow.py
│   │   │   │   ├── loop_steps_workflow_stream.py
│   │   │   │   ├── loop_with_parallel_steps.py
│   │   │   │   └── loop_with_parallel_steps_stream.py
│   │   │   └── __init__.py
│   │   ├── _04_workflows_parallel_execution
│   │   │   ├── async
│   │   │   │   ├── __init__.py
│   │   │   │   ├── parallel_and_condition_steps_stream.py
│   │   │   │   ├── parallel_steps_workflow.py
│   │   │   │   └── parallel_steps_workflow_stream.py
│   │   │   ├── sync
│   │   │   │   ├── __init__.py
│   │   │   │   ├── parallel_and_condition_steps_stream.py
│   │   │   │   ├── parallel_steps_workflow.py
│   │   │   │   └── parallel_steps_workflow_stream.py
│   │   │   └── __init__.py
│   │   ├── _05_workflows_conditional_branching
│   │   │   ├── async
│   │   │   │   ├── router_steps_workflow.py
│   │   │   │   ├── router_steps_workflow_stream.py
│   │   │   │   ├── router_with_loop_steps.py
│   │   │   │   └── selector_for_image_video_generation_pipeline.py
│   │   │   ├── sync
│   │   │   │   ├── router_steps_workflow.py
│   │   │   │   ├── router_steps_workflow_stream.py
│   │   │   │   ├── router_with_loop_steps.py
│   │   │   │   └── selector_for_image_video_generation_pipelines.py
│   │   │   └── __init__.py
│   │   ├── _06_advanced_concepts
│   │   │   ├── _01_structured_io_at_each_level
│   │   │   │   ├── pydantic_model_as_input.py
│   │   │   │   ├── structured_io_at_each_level_agent.py
│   │   │   │   ├── structured_io_at_each_level_agent_stream.py
│   │   │   │   ├── structured_io_at_each_level_function.py
│   │   │   │   ├── structured_io_at_each_level_function_1.py
│   │   │   │   ├── structured_io_at_each_level_function_2.py
│   │   │   │   ├── structured_io_at_each_level_team.py
│   │   │   │   ├── structured_io_at_each_level_team_stream.py
│   │   │   │   └── workflow_with_input_schema.py
│   │   │   ├── _02_early_stopping
│   │   │   │   ├── early_stop_workflow_with_agents.py
│   │   │   │   ├── early_stop_workflow_with_condition.py
│   │   │   │   ├── early_stop_workflow_with_loop.py
│   │   │   │   ├── early_stop_workflow_with_parallel.py
│   │   │   │   ├── early_stop_workflow_with_router.py
│   │   │   │   ├── early_stop_workflow_with_step.py
│   │   │   │   └── early_stop_workflow_with_steps.py
│   │   │   ├── _03_access_previous_step_outputs
│   │   │   │   ├── access_multiple_previous_step_output_stream_2.py
│   │   │   │   ├── access_multiple_previous_steps_output_stream.py
│   │   │   │   └── access_multiple_previous_steps_output_stream_1.py
│   │   │   ├── _04_shared_session_state
│   │   │   │   ├── access_session_state_in_custom_function_step_stream.py
│   │   │   │   ├── access_session_state_in_custom_python_function_step.py
│   │   │   │   ├── condition_with_session_state_in_evaluator_function.py
│   │   │   │   ├── router_with_session_state_in_selector_function.py
│   │   │   │   ├── session_state_with_router_workflow.py
│   │   │   │   ├── shared_session_state_with_agent.py
│   │   │   │   └── shared_session_state_with_team.py
│   │   │   ├── _05_background_execution
│   │   │   │   ├── background_execution_using_websocket
│   │   │   │   └── background_execution_poll.py
│   │   │   ├── _06_guardrails
│   │   │   │   ├── __init__.py
│   │   │   │   └── prompt_injection_workflow.py
│   │   │   ├── _07_workflow_history
│   │   │   │   ├── 01_single_step_continuous_execution_workflow.py
│   │   │   │   ├── 02_workflow_with_history_enabled_for_steps.py
│   │   │   │   ├── 03_enable_history_for_step.py
│   │   │   │   ├── 04_get_history_in_function.py
│   │   │   │   ├── 05_multi_purpose_cli.py
│   │   │   │   ├── 06_intent_routing_with_history.py
│   │   │   │   └── README.md
│   │   │   ├── _08_workflow_agent
│   │   │   │   ├── async
│   │   │   │   ├── sync
│   │   │   │   └── README.md
│   │   │   ├── _09_long_running_workflows
│   │   │   │   ├── 01_workflow_websocket_reconnect.py
│   │   │   │   ├── 02_workflow_events_replay.py
│   │   │   │   └── 03_workflow_disruption_fully_catchup.py
│   │   │   ├── _10_other
│   │   │   │   ├── rename_workflow_session.py
│   │   │   │   ├── store_events_and_events_to_skip_in_a_workflow.py
│   │   │   │   ├── stream_executor_events.py
│   │   │   │   ├── workflow_cancel_a_run.py
│   │   │   │   ├── workflow_metrics_on_run_response.py
│   │   │   │   ├── workflow_tools.py
│   │   │   │   └── workflow_with_image_input.py
│   │   │   └── __init__.py
│   │   ├── assets
│   │   │   ├── condition_steps.png
│   │   │   ├── custom_function_steps.png
│   │   │   ├── early_stop.png
│   │   │   ├── loop_steps.png
│   │   │   ├── parallel_steps.png
│   │   │   ├── router_steps.png
│   │   │   ├── step_io_flow.png
│   │   │   └── workflows_flow.png
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 05_agent_os
│   │   ├── advanced_demo
│   │   │   ├── __init__.py
│   │   │   ├── _agents.py
│   │   │   ├── _teams.py
│   │   │   ├── demo.py
│   │   │   ├── file_output.py
│   │   │   ├── mcp_demo.py
│   │   │   ├── multiple_knowledge_bases.py
│   │   │   ├── reasoning_demo.py
│   │   │   ├── reasoning_model.py
│   │   │   └── teams_demo.py
│   │   ├── background_tasks
│   │   │   ├── background_evals_example.py
│   │   │   ├── background_hooks_decorator.py
│   │   │   ├── background_hooks_example.py
│   │   │   ├── background_hooks_team.py
│   │   │   ├── background_hooks_workflow.py
│   │   │   ├── background_output_evaluation.py
│   │   │   └── README.md
│   │   ├── client
│   │   │   ├── 01_basic_client.py
│   │   │   ├── 02_run_agents.py
│   │   │   ├── 03_memory_operations.py
│   │   │   ├── 04_session_management.py
│   │   │   ├── 05_knowledge_search.py
│   │   │   ├── 06_run_teams.py
│   │   │   ├── 07_run_workflows.py
│   │   │   ├── 08_run_evals.py
│   │   │   ├── 09_upload_content.py
│   │   │   ├── __init__.py
│   │   │   ├── README.md
│   │   │   └── server.py
│   │   ├── client_a2a
│   │   │   ├── servers
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agno_server.py
│   │   │   │   └── google_adk_server.py
│   │   │   ├── 01_basic_messaging.py
│   │   │   ├── 02_streaming.py
│   │   │   ├── 03_multi_turn.py
│   │   │   ├── 04_error_handling.py
│   │   │   ├── 05_connect_to_google_adk.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── customize
│   │   │   ├── __init__.py
│   │   │   ├── custom_fastapi_app.py
│   │   │   ├── custom_health_endpoint.py
│   │   │   ├── custom_lifespan.py
│   │   │   └── override_routes.py
│   │   ├── dbs
│   │   │   ├── surreal_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agents.py
│   │   │   │   ├── db.py
│   │   │   │   ├── run.py
│   │   │   │   ├── teams.py
│   │   │   │   └── workflows.py
│   │   │   ├── __init__.py
│   │   │   ├── async_mongo_demo.py
│   │   │   ├── async_mysql_demo.py
│   │   │   ├── async_postgres_demo.py
│   │   │   ├── dynamo_demo.py
│   │   │   ├── firestore_demo.py
│   │   │   ├── gcs_json_demo.py
│   │   │   ├── json_demo.py
│   │   │   ├── mongo_demo.py
│   │   │   ├── mysql_demo.py
│   │   │   ├── neon_demo.py
│   │   │   ├── postgres_demo.py
│   │   │   ├── redis_demo.py
│   │   │   ├── singlestore_demo.py
│   │   │   ├── sqlite_demo.py
│   │   │   ├── supabase_demo.py
│   │   │   └── surreal_demo.py
│   │   ├── interfaces
│   │   │   ├── a2a
│   │   │   │   ├── multi_agent_a2a
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent_with_tools.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── README.md
│   │   │   │   ├── reasoning_agent.py
│   │   │   │   ├── research_team.py
│   │   │   │   └── structured_output.py
│   │   │   ├── agui
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent_with_tools.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── multiple_instances.py
│   │   │   │   ├── README.md
│   │   │   │   ├── reasoning_agent.py
│   │   │   │   ├── research_team.py
│   │   │   │   └── structured_output.py
│   │   │   ├── slack
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent_with_user_memory.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_workflow.py
│   │   │   │   ├── multiple_instances.py
│   │   │   │   ├── README.md
│   │   │   │   └── reasoning_agent.py
│   │   │   ├── whatsapp
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent_with_media.py
│   │   │   │   ├── agent_with_user_memory.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── image_generation_model.py
│   │   │   │   ├── image_generation_tools.py
│   │   │   │   ├── multiple_instances.py
│   │   │   │   ├── readme.md
│   │   │   │   └── reasoning_agent.py
│   │   │   └── __init__.py
│   │   ├── knowledge
│   │   │   ├── __init__.py
│   │   │   ├── agentos_excel_analyst.py
│   │   │   ├── agentos_knowledge.py
│   │   │   ├── agentos_knowledge_async.py
│   │   │   └── agno_docs_agent.py
│   │   ├── mcp_demo
│   │   │   ├── dynamic_headers
│   │   │   │   ├── client.py
│   │   │   │   └── server.py
│   │   │   ├── __init__.py
│   │   │   ├── enable_mcp_example.py
│   │   │   ├── mcp_tools_advanced_example.py
│   │   │   ├── mcp_tools_example.py
│   │   │   ├── mcp_tools_existing_lifespan.py
│   │   │   └── test_client.py
│   │   ├── middleware
│   │   │   ├── __init__.py
│   │   │   ├── agent_os_with_custom_middleware.py
│   │   │   ├── agent_os_with_jwt_middleware.py
│   │   │   ├── agent_os_with_jwt_middleware_cookies.py
│   │   │   ├── custom_fastapi_app_with_jwt_middleware.py
│   │   │   └── extract_content_middleware.py
│   │   ├── os_config
│   │   │   ├── __init__.py
│   │   │   ├── basic.py
│   │   │   ├── config.yaml
│   │   │   └── yaml_config.py
│   │   ├── rbac
│   │   │   ├── asymmetric
│   │   │   │   ├── basic.py
│   │   │   │   └── custom_scope_mappings.py
│   │   │   ├── symmetric
│   │   │   │   ├── advanced_scopes.py
│   │   │   │   ├── agent_permissions.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── custom_scope_mappings.py
│   │   │   │   └── with_cookie.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── remote
│   │   │   ├── 01_remote_agent.py
│   │   │   ├── 02_remote_team.py
│   │   │   ├── 03_remote_agno_a2a_agent.py
│   │   │   ├── 04_remote_adk_agent.py
│   │   │   ├── 05_agent_os_gateway.py
│   │   │   ├── adk_server.py
│   │   │   ├── agno_a2a_server.py
│   │   │   ├── README.md
│   │   │   └── server.py
│   │   ├── skills
│   │   │   ├── sample_skills
│   │   │   │   └── system-info
│   │   │   ├── __init__.py
│   │   │   ├── README.md
│   │   │   └── skills_with_agentos.py
│   │   ├── tracing
│   │   │   ├── dbs
│   │   │   │   ├── basic_agent_with_async_mysql.py
│   │   │   │   ├── basic_agent_with_async_postgres.py
│   │   │   │   ├── basic_agent_with_async_sqlite.py
│   │   │   │   ├── basic_agent_with_dynamodb.py
│   │   │   │   ├── basic_agent_with_firestore.py
│   │   │   │   ├── basic_agent_with_gcs_json_db.py
│   │   │   │   ├── basic_agent_with_jsondb.py
│   │   │   │   ├── basic_agent_with_mongodb.py
│   │   │   │   ├── basic_agent_with_mysql.py
│   │   │   │   ├── basic_agent_with_postgresdb.py
│   │   │   │   ├── basic_agent_with_redis.py
│   │   │   │   ├── basic_agent_with_singlestore.py
│   │   │   │   ├── basic_agent_with_sqlite.py
│   │   │   │   └── basic_agent_with_surrealdb.py
│   │   │   ├── 01_basic_agent_tracing.py
│   │   │   ├── 02_basic_team_tracing.py
│   │   │   ├── 03_agent_with_knowledge_tracing.py
│   │   │   ├── 04_agent_with_reasoning_tools_tracing.py
│   │   │   ├── 05_basic_workflow_tracing.py
│   │   │   ├── 06_tracing_with_multi_db_scenario.py
│   │   │   ├── 07_tracing_with_multi_db_and_tracing_flag.py
│   │   │   └── __init__.py
│   │   ├── workflow
│   │   │   ├── __init__.py
│   │   │   ├── basic_chat_workflow_agent.py
│   │   │   ├── basic_workflow.py
│   │   │   ├── basic_workflow_team.py
│   │   │   ├── customer_research_workflow_parallel.py
│   │   │   ├── workflow_with_conditional.py
│   │   │   ├── workflow_with_custom_function.py
│   │   │   ├── workflow_with_custom_function_stream.py
│   │   │   ├── workflow_with_custom_function_updating_session_state.py
│   │   │   ├── workflow_with_history.py
│   │   │   ├── workflow_with_input_schema.py
│   │   │   ├── workflow_with_loop.py
│   │   │   ├── workflow_with_nested_steps.py
│   │   │   ├── workflow_with_parallel.py
│   │   │   ├── workflow_with_parallel_and_custom_function_step_stream.py
│   │   │   ├── workflow_with_router.py
│   │   │   └── workflow_with_steps.py
│   │   ├── __init__.py
│   │   ├── agent_with_input_schema.py
│   │   ├── agent_with_output_schema.py
│   │   ├── agno_agent.py
│   │   ├── all_interfaces.py
│   │   ├── basic.py
│   │   ├── CLAUDE.md
│   │   ├── demo.py
│   │   ├── evals_demo.py
│   │   ├── guardrails_demo.py
│   │   ├── handle_custom_events.py
│   │   ├── pass_dependencies_to_agent.py
│   │   ├── README.md
│   │   ├── shopify_demo.py
│   │   ├── team_with_input_schema.py
│   │   ├── team_with_output_schema.py
│   │   └── update_from_lifespan.py
│   ├── 06_agent_os
│   │   ├── dbs
│   │   │   └── agentos_default_db.py
│   │   └── interfaces
│   │       └── agui
│   │           └── agent_with_silent_tools.py
│   ├── 06_storage
│   │   ├── dynamodb
│   │   │   ├── __init__.py
│   │   │   ├── dynamo_for_agent.py
│   │   │   ├── dynamo_for_team.py
│   │   │   └── README.md
│   │   ├── examples
│   │   │   ├── __init__.py
│   │   │   ├── multi_user_multi_session.py
│   │   │   ├── README.md
│   │   │   └── selecting_tables.py
│   │   ├── firestore
│   │   │   ├── __init__.py
│   │   │   ├── firestore_for_agent.py
│   │   │   └── README.md
│   │   ├── gcs
│   │   │   ├── __init__.py
│   │   │   ├── gcs_json_for_agent.py
│   │   │   └── README.md
│   │   ├── in_memory
│   │   │   ├── __init__.py
│   │   │   ├── in_memory_storage_for_agent.py
│   │   │   ├── in_memory_storage_for_team.py
│   │   │   ├── in_memory_storage_for_workflow.py
│   │   │   └── README.md
│   │   ├── json_db
│   │   │   ├── __init__.py
│   │   │   ├── json_for_agent.py
│   │   │   ├── json_for_team.py
│   │   │   ├── json_for_workflows.py
│   │   │   └── README.md
│   │   ├── mongo
│   │   │   ├── async_mongo
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_mongodb_for_agent.py
│   │   │   │   ├── async_mongodb_for_team.py
│   │   │   │   └── async_mongodb_for_workflow.py
│   │   │   ├── __init__.py
│   │   │   ├── mongodb_for_agent.py
│   │   │   ├── mongodb_for_team.py
│   │   │   └── README.md
│   │   ├── mysql
│   │   │   ├── async_mysql
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_mysql_for_agent.py
│   │   │   │   ├── async_mysql_for_team.py
│   │   │   │   └── async_mysql_for_workflow.py
│   │   │   ├── __init__.py
│   │   │   ├── mysql_for_agent.py
│   │   │   ├── mysql_for_team.py
│   │   │   └── README.md
│   │   ├── postgres
│   │   │   ├── async_postgres
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_postgres_for_agent.py
│   │   │   │   ├── async_postgres_for_team.py
│   │   │   │   └── async_postgres_for_workflow.py
│   │   │   ├── __init__.py
│   │   │   ├── postgres_for_agent.py
│   │   │   ├── postgres_for_team.py
│   │   │   ├── postgres_for_workflow.py
│   │   │   └── README.md
│   │   ├── redis
│   │   │   ├── __init__.py
│   │   │   ├── README.md
│   │   │   ├── redis_for_agent.py
│   │   │   ├── redis_for_team.py
│   │   │   └── redis_for_workflow.py
│   │   ├── singlestore
│   │   │   ├── __init__.py
│   │   │   ├── README.md
│   │   │   ├── singlestore_for_agent.py
│   │   │   └── singlestore_for_team.py
│   │   ├── sqlite
│   │   │   ├── async_sqlite
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_sqlite_for_agent.py
│   │   │   │   ├── async_sqlite_for_team.py
│   │   │   │   └── async_sqlite_for_workflow.py
│   │   │   ├── __init__.py
│   │   │   ├── README.md
│   │   │   ├── sqlite_for_agent.py
│   │   │   ├── sqlite_for_team.py
│   │   │   └── sqlite_for_workflow.py
│   │   ├── surrealdb
│   │   │   ├── __init__.py
│   │   │   ├── README.md
│   │   │   ├── surrealdb_for_agent.py
│   │   │   ├── surrealdb_for_team.py
│   │   │   └── surrealdb_for_workflow.py
│   │   ├── 01_persistent_session_storage.py
│   │   ├── 02_session_summary.py
│   │   ├── 03_chat_history.py
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 07_knowledge
│   │   ├── basic_operations
│   │   │   ├── async
│   │   │   │   ├── 01_from_path.py
│   │   │   │   ├── 02_from_url.py
│   │   │   │   ├── 03_from_topic.py
│   │   │   │   ├── 04_from_multiple.py
│   │   │   │   ├── 05_from_youtube.py
│   │   │   │   ├── 06_from_s3.py
│   │   │   │   ├── 07_from_gcs.py
│   │   │   │   ├── 08_include_exclude_files.py
│   │   │   │   ├── 09_remove_content.py
│   │   │   │   ├── 10_remove_vectors.py
│   │   │   │   ├── 11_skip_if_exists.py
│   │   │   │   ├── 12_skip_if_exists_contentsdb.py
│   │   │   │   ├── 13_specify_reader.py
│   │   │   │   ├── 14_text_content.py
│   │   │   │   ├── 15_batching.py
│   │   │   │   └── __init__.py
│   │   │   ├── sync
│   │   │   │   ├── 01_from_path.py
│   │   │   │   ├── 02_from_url.py
│   │   │   │   ├── 03_from_topic.py
│   │   │   │   ├── 04_from_multiple.py
│   │   │   │   ├── 05_from_youtube.py
│   │   │   │   ├── 06_from_s3.py
│   │   │   │   ├── 07_from_gcs.py
│   │   │   │   ├── 08_include_exclude_files.py
│   │   │   │   ├── 09_remove_content.py
│   │   │   │   ├── 10_remove_vectors.py
│   │   │   │   ├── 11_skip_if_exists.py
│   │   │   │   ├── 12_skip_if_exists_contentsdb.py
│   │   │   │   ├── 13_specify_reader.py
│   │   │   │   ├── 14_text_content.py
│   │   │   │   ├── 15_batching.py
│   │   │   │   ├── 16_knowledge_instructions.py
│   │   │   │   └── __init__.py
│   │   │   └── __init__.py
│   │   ├── chunking
│   │   │   ├── __init__.py
│   │   │   ├── agentic_chunking.py
│   │   │   ├── code_chunking.py
│   │   │   ├── code_chunking_custom_tokenizer.py
│   │   │   ├── csv_row_chunking.py
│   │   │   ├── custom_strategy_example.py
│   │   │   ├── document_chunking.py
│   │   │   ├── fixed_size_chunking.py
│   │   │   ├── markdown_chunking.py
│   │   │   ├── README.md
│   │   │   ├── recursive_chunking.py
│   │   │   ├── semantic_chunking.py
│   │   │   ├── semantic_chunking_agno_embedder.py
│   │   │   └── semantic_chunking_chonkie_embedder.py
│   │   ├── cloud
│   │   │   ├── azure_blob.py
│   │   │   ├── cloud_agentos.py
│   │   │   ├── github.py
│   │   │   └── sharepoint.py
│   │   ├── custom_retriever
│   │   │   ├── __init__.py
│   │   │   ├── async_retriever.py
│   │   │   ├── README.md
│   │   │   ├── retriever.py
│   │   │   └── retriever_with_dependencies.py
│   │   ├── embedders
│   │   │   ├── __init__.py
│   │   │   ├── aws_bedrock_embedder.py
│   │   │   ├── aws_bedrock_embedder_v4.py
│   │   │   ├── azure_embedder.py
│   │   │   ├── azure_embedder_batching.py
│   │   │   ├── cohere_embedder.py
│   │   │   ├── cohere_embedder_batching.py
│   │   │   ├── fireworks_embedder.py
│   │   │   ├── fireworks_embedder_batching.py
│   │   │   ├── gemini_embedder.py
│   │   │   ├── gemini_embedder_batching.py
│   │   │   ├── huggingface_embedder.py
│   │   │   ├── jina_embedder.py
│   │   │   ├── jina_embedder_batching.py
│   │   │   ├── langdb_embedder.py
│   │   │   ├── mistral_embedder.py
│   │   │   ├── mistral_embedder_batching.py
│   │   │   ├── nebius_embedder.py
│   │   │   ├── ollama_embedder.py
│   │   │   ├── openai_embedder.py
│   │   │   ├── openai_embedder_batching.py
│   │   │   ├── qdrant_fastembed.py
│   │   │   ├── README.md
│   │   │   ├── sentence_transformer_embedder.py
│   │   │   ├── together_embedder.py
│   │   │   ├── vllm_embedder_batching_local.py
│   │   │   ├── vllm_embedder_batching_remote.py
│   │   │   ├── vllm_embedder_local.py
│   │   │   ├── vllm_embedder_remote.py
│   │   │   ├── voyageai_embedder.py
│   │   │   └── voyageai_embedder_batching.py
│   │   ├── filters
│   │   │   ├── vector_dbs
│   │   │   │   ├── __init__.py
│   │   │   │   ├── filtering_chroma_db.py
│   │   │   │   ├── filtering_lance_db.py
│   │   │   │   ├── filtering_milvus.py
│   │   │   │   ├── filtering_mongo_db.py
│   │   │   │   ├── filtering_pgvector.py
│   │   │   │   ├── filtering_pinecone.py
│   │   │   │   ├── filtering_qdrant_db.py
│   │   │   │   ├── filtering_surrealdb.py
│   │   │   │   └── filtering_weaviate.py
│   │   │   ├── __init__.py
│   │   │   ├── agentic_filtering.py
│   │   │   ├── agentic_filtering_with_output_schema.py
│   │   │   ├── async_agentic_filtering.py
│   │   │   ├── async_filtering.py
│   │   │   ├── filtering.py
│   │   │   ├── filtering_on_load.py
│   │   │   ├── filtering_with_conditions_on_agent.py
│   │   │   ├── filtering_with_conditions_on_team.py
│   │   │   ├── filtering_with_invalid_keys.py
│   │   │   └── README.md
│   │   ├── protocol
│   │   │   └── file_system.py
│   │   ├── readers
│   │   │   ├── __init__.py
│   │   │   ├── arxiv_reader.py
│   │   │   ├── arxiv_reader_async.py
│   │   │   ├── csv_field_labeled_reader.py
│   │   │   ├── csv_reader.py
│   │   │   ├── csv_reader_async.py
│   │   │   ├── csv_reader_custom_encodings.py
│   │   │   ├── csv_reader_url_async.py
│   │   │   ├── doc_kb_async.py
│   │   │   ├── excel_legacy_xls.py
│   │   │   ├── excel_reader.py
│   │   │   ├── firecrawl_reader.py
│   │   │   ├── json_reader.py
│   │   │   ├── markdown_reader_async.py
│   │   │   ├── md_reader_async.py
│   │   │   ├── pdf_reader_async.py
│   │   │   ├── pdf_reader_password.py
│   │   │   ├── pdf_reader_url_password.py
│   │   │   ├── pptx_reader.py
│   │   │   ├── pptx_reader_async.py
│   │   │   ├── README.md
│   │   │   ├── tavily_reader.py
│   │   │   ├── tavily_reader_async.py
│   │   │   ├── web_reader.py
│   │   │   ├── web_search_reader.py
│   │   │   ├── web_search_reader_async.py
│   │   │   └── website_reader.py
│   │   ├── search_type
│   │   │   ├── __init__.py
│   │   │   ├── hybrid_search.py
│   │   │   ├── keyword_search.py
│   │   │   ├── README.md
│   │   │   └── vector_search.py
│   │   ├── testing_resources
│   │   │   ├── coffee.md
│   │   │   ├── cv_1.pdf
│   │   │   ├── cv_2.pdf
│   │   │   ├── legacy_data.xls
│   │   │   ├── sample_products.xlsx
│   │   │   └── state_of_the_union.txt
│   │   ├── vector_db
│   │   │   ├── cassandra_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_cassandra_db.py
│   │   │   │   ├── async_cassandra_db_with_batch_embedder.py
│   │   │   │   └── cassandra_db.py
│   │   │   ├── chroma_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_chroma_db.py
│   │   │   │   ├── async_chroma_db_with_batch_embedder.py
│   │   │   │   ├── chroma_db.py
│   │   │   │   └── chroma_db_hybrid_search.py
│   │   │   ├── clickhouse_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_clickhouse.py
│   │   │   │   ├── async_clickhouse_with_batch_embedder.py
│   │   │   │   └── clickhouse.py
│   │   │   ├── couchbase_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_couchbase_db.py
│   │   │   │   ├── async_couchbase_db_with_batch_embedder.py
│   │   │   │   └── couchbase_db.py
│   │   │   ├── lance_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_lance_db_with_batch_embedder.py
│   │   │   │   ├── lance_db.py
│   │   │   │   ├── lance_db_hybrid_search.py
│   │   │   │   └── lance_db_with_mistral_embedder.py
│   │   │   ├── langchain
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_langchain_db.py
│   │   │   │   └── langchain_db.py
│   │   │   ├── lightrag
│   │   │   │   ├── __init__.py
│   │   │   │   └── lightrag.py
│   │   │   ├── llamaindex_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_llamaindex_db.py
│   │   │   │   └── llamaindex_db.py
│   │   │   ├── milvus_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_milvus_db.py
│   │   │   │   ├── async_milvus_db_hybrid_search.py
│   │   │   │   ├── async_milvus_db_with_batch_embedder.py
│   │   │   │   ├── milvus_db.py
│   │   │   │   ├── milvus_db_hybrid_search.py
│   │   │   │   └── milvus_db_range_search.py
│   │   │   ├── mongo_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_mongo_db.py
│   │   │   │   ├── async_mongo_db_with_batch_embedder.py
│   │   │   │   ├── cosmos_mongodb_vcore.py
│   │   │   │   ├── mongo_db.py
│   │   │   │   └── mongo_db_hybrid_search.py
│   │   │   ├── pgvector
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_pg_vector.py
│   │   │   │   ├── async_pg_vector_with_batch_embedder.py
│   │   │   │   ├── pgvector_db.py
│   │   │   │   ├── pgvector_hybrid_search.py
│   │   │   │   └── pgvector_with_bedrock_reranker.py
│   │   │   ├── pinecone_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_pinecone_db_with_batch_embedder.py
│   │   │   │   └── pinecone_db.py
│   │   │   ├── qdrant_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_qdrant_db.py
│   │   │   │   ├── async_qdrant_db_with_batch_embedder.py
│   │   │   │   ├── qdrant_db.py
│   │   │   │   └── qdrant_db_hybrid_search.py
│   │   │   ├── redis_db
│   │   │   │   ├── async_redis_db.py
│   │   │   │   ├── redis_db.py
│   │   │   │   └── redis_db_with_cohere_reranker.py
│   │   │   ├── singlestore_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_singlestore_db_with_batch_embedder.py
│   │   │   │   └── singlestore_db.py
│   │   │   ├── surrealdb
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_surreal_db.py
│   │   │   │   └── surreal_db.py
│   │   │   ├── upstash_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_upstash_db_with_batch_embedder.py
│   │   │   │   └── upstash_db.py
│   │   │   ├── weaviate_db
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_weaviate_db.py
│   │   │   │   ├── async_weaviate_db_with_batch_embedder.py
│   │   │   │   ├── weaviate_db.py
│   │   │   │   ├── weaviate_db_hybrid_search.py
│   │   │   │   └── weaviate_db_upsert.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   ├── knowledge_tools.py
│   │   ├── quickstart.py
│   │   └── README.md
│   ├── 08_learning
│   │   ├── 00_quickstart
│   │   │   ├── 01_always_learn.py
│   │   │   ├── 02_agentic_learn.py
│   │   │   └── 03_learned_knowledge.py
│   │   ├── 01_basics
│   │   │   ├── 1a_user_profile_always.py
│   │   │   ├── 1b_user_profile_agentic.py
│   │   │   ├── 2a_user_memory_always.py
│   │   │   ├── 2b_user_memory_agentic.py
│   │   │   ├── 3a_session_context_summary.py
│   │   │   ├── 3b_session_context_planning.py
│   │   │   ├── 4_learned_knowledge.py
│   │   │   ├── 5a_entity_memory_always.py
│   │   │   └── 5b_entity_memory_agentic.py
│   │   ├── 02_user_profile
│   │   │   ├── 01_always_extraction.py
│   │   │   ├── 02_agentic_mode.py
│   │   │   └── 03_custom_schema.py
│   │   ├── 03_session_context
│   │   │   ├── 01_summary_mode.py
│   │   │   └── 02_planning_mode.py
│   │   ├── 04_entity_memory
│   │   │   ├── 01_facts_and_events.py
│   │   │   └── 02_entity_relationships.py
│   │   ├── 05_learned_knowledge
│   │   │   ├── 01_agentic_mode.py
│   │   │   └── 02_propose_mode.py
│   │   ├── 06_quick_tests
│   │   │   ├── 01_async_user_profile.py
│   │   │   ├── 02_learning_true_shorthand.py
│   │   │   ├── 03_no_db_graceful.py
│   │   │   └── 04_claude_model.py
│   │   ├── 07_patterns
│   │   │   ├── personal_assistant.py
│   │   │   └── support_agent.py
│   │   ├── 08_custom_stores
│   │   │   ├── 01_minimal_custom_store.py
│   │   │   └── 02_custom_store_with_db.py
│   │   ├── 09_decision_logs
│   │   │   ├── 1_basic_decision_log.py
│   │   │   └── 2_decision_log_always.py
│   │   ├── .gitignore
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   ├── generate_requirements.sh
│   │   ├── README.md
│   │   ├── requirements.in
│   │   ├── requirements.txt
│   │   ├── setup_venv.sh
│   │   └── TEST_LOG.md
│   ├── 09_evals
│   │   ├── accuracy
│   │   │   ├── __init__.py
│   │   │   ├── accuracy_9_11_bigger_or_9_99.py
│   │   │   ├── accuracy_async.py
│   │   │   ├── accuracy_basic.py
│   │   │   ├── accuracy_team.py
│   │   │   ├── accuracy_with_given_answer.py
│   │   │   ├── accuracy_with_tools.py
│   │   │   ├── db_logging.py
│   │   │   └── evaluator_agent.py
│   │   ├── agent_as_judge
│   │   │   ├── __init__.py
│   │   │   ├── agent_as_judge_async.py
│   │   │   ├── agent_as_judge_basic.py
│   │   │   ├── agent_as_judge_batch.py
│   │   │   ├── agent_as_judge_binary.py
│   │   │   ├── agent_as_judge_custom_evaluator.py
│   │   │   ├── agent_as_judge_post_hook.py
│   │   │   ├── agent_as_judge_post_hook_async.py
│   │   │   ├── agent_as_judge_team.py
│   │   │   ├── agent_as_judge_team_post_hook.py
│   │   │   ├── agent_as_judge_with_guidelines.py
│   │   │   └── agent_as_judge_with_tools.py
│   │   ├── performance
│   │   │   ├── comparison
│   │   │   │   ├── __init__.py
│   │   │   │   ├── autogen_instantiation.py
│   │   │   │   ├── crewai_instantiation.py
│   │   │   │   ├── langgraph_instantiation.py
│   │   │   │   ├── openai_agents_instantiation.py
│   │   │   │   ├── pydantic_ai_instantiation.py
│   │   │   │   └── smolagents_instantiation.py
│   │   │   ├── __init__.py
│   │   │   ├── async_function.py
│   │   │   ├── db_logging.py
│   │   │   ├── instantiate_agent.py
│   │   │   ├── instantiate_agent_with_tool.py
│   │   │   ├── instantiate_team.py
│   │   │   ├── response_with_memory_updates.py
│   │   │   ├── response_with_storage.py
│   │   │   ├── simple_response.py
│   │   │   ├── team_response_with_memory_and_reasoning.py
│   │   │   ├── team_response_with_memory_multi_user.py
│   │   │   └── team_response_with_memory_simple.py
│   │   ├── reliability
│   │   │   ├── multiple_tool_calls
│   │   │   │   ├── __init__.py
│   │   │   │   └── calculator.py
│   │   │   ├── single_tool_calls
│   │   │   │   ├── __init__.py
│   │   │   │   └── calculator.py
│   │   │   ├── team
│   │   │   │   ├── __init__.py
│   │   │   │   └── ai_news.py
│   │   │   ├── __init__.py
│   │   │   ├── db_logging.py
│   │   │   └── reliability_async.py
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 10_reasoning
│   │   ├── agents
│   │   │   ├── __init__.py
│   │   │   ├── analyse_treaty_of_versailles.py
│   │   │   ├── capture_reasoning_content_default_COT.py
│   │   │   ├── cerebras_llama_default_COT.py
│   │   │   ├── default_chain_of_thought.py
│   │   │   ├── fibonacci.py
│   │   │   ├── finance_agent.py
│   │   │   ├── ibm_watsonx_default_COT.py
│   │   │   ├── is_9_11_bigger_than_9_9.py
│   │   │   ├── life_in_500000_years.py
│   │   │   ├── logical_puzzle.py
│   │   │   ├── mathematical_proof.py
│   │   │   ├── mistral_reasoning_cot.py
│   │   │   ├── python_101_curriculum.py
│   │   │   ├── scientific_research.py
│   │   │   ├── ship_of_theseus.py
│   │   │   ├── strawberry.py
│   │   │   └── trolley_problem.py
│   │   ├── models
│   │   │   ├── anthropic
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_reasoning_stream.py
│   │   │   │   ├── basic_reasoning.py
│   │   │   │   └── basic_reasoning_stream.py
│   │   │   ├── azure_ai_foundry
│   │   │   │   ├── __init__.py
│   │   │   │   ├── reasoning_model_deepseek.py
│   │   │   │   └── reasoning_model_stream_deepseek.py
│   │   │   ├── azure_openai
│   │   │   │   ├── __init__.py
│   │   │   │   ├── basic_reasoning_stream.py
│   │   │   │   ├── o3_mini_with_tools.py
│   │   │   │   └── reasoning_model_gpt_4_1.py
│   │   │   ├── deepseek
│   │   │   │   ├── 9_11_or_9_9.py
│   │   │   │   ├── __init__.py
│   │   │   │   ├── analyse_treaty_of_versailles.py
│   │   │   │   ├── ethical_dilemma.py
│   │   │   │   ├── fibonacci.py
│   │   │   │   ├── finance_agent.py
│   │   │   │   ├── life_in_500000_years.py
│   │   │   │   ├── logical_puzzle.py
│   │   │   │   ├── mathematical_proof.py
│   │   │   │   ├── plan_itenerary.py
│   │   │   │   ├── python_101_curriculum.py
│   │   │   │   ├── scientific_research.py
│   │   │   │   ├── ship_of_theseus.py
│   │   │   │   ├── strawberry.py
│   │   │   │   └── trolley_problem.py
│   │   │   ├── gemini
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_reasoning_stream.py
│   │   │   │   ├── basic_reasoning.py
│   │   │   │   └── basic_reasoning_stream.py
│   │   │   ├── groq
│   │   │   │   ├── 9_11_or_9_9.py
│   │   │   │   ├── __init__.py
│   │   │   │   ├── deepseek_plus_claude.py
│   │   │   │   └── fast_reasoning.py
│   │   │   ├── ollama
│   │   │   │   ├── __init__.py
│   │   │   │   ├── local_reasoning.py
│   │   │   │   └── reasoning_model_deepseek.py
│   │   │   ├── openai
│   │   │   │   ├── __init__.py
│   │   │   │   ├── o3_mini.py
│   │   │   │   ├── o3_mini_with_tools.py
│   │   │   │   ├── reasoning_effort.py
│   │   │   │   ├── reasoning_model_gpt_4_1.py
│   │   │   │   ├── reasoning_stream.py
│   │   │   │   └── reasoning_summary.py
│   │   │   ├── vertex_ai
│   │   │   │   └── basic_reasoning_stream.py
│   │   │   ├── xai
│   │   │   │   ├── __init__.py
│   │   │   │   └── reasoning_effort.py
│   │   │   └── __init__.py
│   │   ├── teams
│   │   │   ├── __init__.py
│   │   │   ├── finance_team_chain_of_thought.py
│   │   │   ├── knowledge_tool_team.py
│   │   │   └── reasoning_finance_team.py
│   │   ├── tools
│   │   │   ├── __init__.py
│   │   │   ├── azure_openai_reasoning_tools.py
│   │   │   ├── capture_reasoning_content_knowledge_tools.py
│   │   │   ├── capture_reasoning_content_reasoning_tools.py
│   │   │   ├── cerebras_llama_reasoning_tools.py
│   │   │   ├── claude_reasoning_tools.py
│   │   │   ├── gemini_finance_agent.py
│   │   │   ├── gemini_reasoning_tools.py
│   │   │   ├── groq_llama_finance_agent.py
│   │   │   ├── ibm_watsonx_reasoning_tools.py
│   │   │   ├── knowledge_tools.py
│   │   │   ├── llama_reasoning_tools.py
│   │   │   ├── memory_tools.py
│   │   │   ├── ollama_reasoning_tools.py
│   │   │   ├── openai_reasoning_tools.py
│   │   │   ├── reasoning_tools.py
│   │   │   ├── vercel_reasoning_tools.py
│   │   │   └── workflow_tools.py
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 80_memory
│   │   ├── memory_manager
│   │   │   ├── surrealdb
│   │   │   │   ├── custom_memory_instructions.py
│   │   │   │   ├── db_tools_control.py
│   │   │   │   ├── memory_creation.py
│   │   │   │   ├── memory_search_surreal.py
│   │   │   │   └── standalone_memory_surreal.py
│   │   │   ├── 01_standalone_memory.py
│   │   │   ├── 02_memory_creation.py
│   │   │   ├── 03_custom_memory_instructions.py
│   │   │   ├── 04_memory_search.py
│   │   │   ├── 05_db_tools_control.py
│   │   │   └── README.md
│   │   ├── optimize_memories
│   │   │   ├── 01_memory_summarize_strategy.py
│   │   │   └── 02_custom_memory_strategy.py
│   │   ├── 01_agent_with_memory.py
│   │   ├── 02_agentic_memory.py
│   │   ├── 03_agents_share_memory.py
│   │   ├── 04_custom_memory_manager.py
│   │   ├── 05_multi_user_multi_session_chat.py
│   │   ├── 06_multi_user_multi_session_chat_concurrent.py
│   │   ├── 07_share_memory_and_history_between_agents.py
│   │   ├── 08_memory_tools.py
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 90_models
│   │   ├── aimlapi
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── image_agent.py
│   │   │   ├── image_agent_bytes.py
│   │   │   ├── image_agent_with_memory.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   └── tool_use.py
│   │   ├── anthropic
│   │   │   ├── skills
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent_with_documents.py
│   │   │   │   ├── agent_with_excel.py
│   │   │   │   ├── agent_with_powerpoint.py
│   │   │   │   ├── file_download_helper.py
│   │   │   │   ├── multi_skill_agent.py
│   │   │   │   └── README.md
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── basic_with_timeout.py
│   │   │   ├── betas.py
│   │   │   ├── code_execution.py
│   │   │   ├── context_management.py
│   │   │   ├── db.py
│   │   │   ├── financial_analyst_thinking.py
│   │   │   ├── image_input_bytes.py
│   │   │   ├── image_input_file_upload.py
│   │   │   ├── image_input_local_file.py
│   │   │   ├── image_input_url.py
│   │   │   ├── knowledge.py
│   │   │   ├── mcp_connector.py
│   │   │   ├── memory.py
│   │   │   ├── pdf_input_bytes.py
│   │   │   ├── pdf_input_file_upload.py
│   │   │   ├── pdf_input_local.py
│   │   │   ├── pdf_input_url.py
│   │   │   ├── prompt_caching.py
│   │   │   ├── prompt_caching_extended.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── structured_output_stream.py
│   │   │   ├── structured_output_strict_tools.py
│   │   │   ├── thinking.py
│   │   │   ├── thinking_stream.py
│   │   │   ├── tool_use.py
│   │   │   ├── tool_use_stream.py
│   │   │   ├── web_fetch.py
│   │   │   └── web_search.py
│   │   ├── aws
│   │   │   ├── bedrock
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_tool_use_stream.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── image_agent_bytes.py
│   │   │   │   ├── pdf_agent_bytes.py
│   │   │   │   ├── README.md
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── tool_use.py
│   │   │   │   └── tool_use_stream.py
│   │   │   ├── claude
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── db.py
│   │   │   │   ├── image_agent.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── README.md
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── tool_use.py
│   │   │   │   └── tool_use_stream.py
│   │   │   ├── __init__.py
│   │   │   └── retry.py
│   │   ├── azure
│   │   │   ├── ai_foundry
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── db.py
│   │   │   │   ├── demo_cohere.py
│   │   │   │   ├── demo_mistral.py
│   │   │   │   ├── image_agent.py
│   │   │   │   ├── image_agent_bytes.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── README.md
│   │   │   │   ├── structured_output.py
│   │   │   │   └── tool_use.py
│   │   │   ├── openai
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── db.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── README.md
│   │   │   │   ├── structured_output.py
│   │   │   │   └── tool_use.py
│   │   │   ├── __init__.py
│   │   │   └── retry.py
│   │   ├── cerebras
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── async_tool_use_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── db.py
│   │   │   ├── knowledge.py
│   │   │   ├── oss_gpt.py
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── cerebras_openai
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── async_tool_use_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── db.py
│   │   │   ├── knowledge.py
│   │   │   ├── oss_gpt.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── clients
│   │   │   ├── __init__.py
│   │   │   └── http_client_caching.py
│   │   ├── cohere
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_structured_output.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── db.py
│   │   │   ├── image_agent.py
│   │   │   ├── image_agent_bytes.py
│   │   │   ├── image_agent_local_file.py
│   │   │   ├── knowledge.py
│   │   │   ├── memory.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── cometapi
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── async_tool_use_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── image_agent.py
│   │   │   ├── image_agent_with_memory.py
│   │   │   ├── multi_model.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── dashscope
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_image_agent.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── image_agent.py
│   │   │   ├── image_agent_bytes.py
│   │   │   ├── knowledge_tools.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── thinking_agent.py
│   │   │   └── tool_use.py
│   │   ├── deepinfra
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── json_output.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   └── tool_use.py
│   │   ├── deepseek
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_streaming.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   ├── reasoning_agent.py
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── thinking_tool_calls.py
│   │   │   └── tool_use.py
│   │   ├── fireworks
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   └── tool_use.py
│   │   ├── google
│   │   │   ├── gemini
│   │   │   │   ├── documents
│   │   │   │   ├── .gitignore
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent_with_thinking_budget.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_image_editing.py
│   │   │   │   ├── async_image_generation.py
│   │   │   │   ├── async_image_generation_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── audio_input_bytes_content.py
│   │   │   │   ├── audio_input_file_upload.py
│   │   │   │   ├── audio_input_local_file_upload.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── db.py
│   │   │   │   ├── external_url_input.py
│   │   │   │   ├── file_search_advanced.py
│   │   │   │   ├── file_search_basic.py
│   │   │   │   ├── file_search_rag_pipeline.py
│   │   │   │   ├── file_upload_with_cache.py
│   │   │   │   ├── gcs_file_input.py
│   │   │   │   ├── gemini_2_to_3.py
│   │   │   │   ├── gemini_3_pro.py
│   │   │   │   ├── gemini_3_pro_thinking_level.py
│   │   │   │   ├── grounding.py
│   │   │   │   ├── image_editing.py
│   │   │   │   ├── image_generation.py
│   │   │   │   ├── image_generation_stream.py
│   │   │   │   ├── image_input.py
│   │   │   │   ├── image_input_file_upload.py
│   │   │   │   ├── imagen_tool.py
│   │   │   │   ├── imagen_tool_advanced.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── pdf_input_file_upload.py
│   │   │   │   ├── pdf_input_local.py
│   │   │   │   ├── pdf_input_url.py
│   │   │   │   ├── README.md
│   │   │   │   ├── retry.py
│   │   │   │   ├── s3_url_file_input.py
│   │   │   │   ├── search.py
│   │   │   │   ├── search_stream.py
│   │   │   │   ├── storage_and_memory.py
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── structured_output_stream.py
│   │   │   │   ├── text_to_speech.py
│   │   │   │   ├── thinking_agent.py
│   │   │   │   ├── thinking_agent_stream.py
│   │   │   │   ├── tool_use.py
│   │   │   │   ├── tool_use_stream.py
│   │   │   │   ├── url_context.py
│   │   │   │   ├── url_context_stream.py
│   │   │   │   ├── url_context_with_search.py
│   │   │   │   ├── vertex_ai_search.py
│   │   │   │   ├── vertexai.py
│   │   │   │   ├── vertexai_with_credentials.py
│   │   │   │   ├── video_input_bytes_content.py
│   │   │   │   ├── video_input_file_upload.py
│   │   │   │   ├── video_input_local_file_upload.py
│   │   │   │   └── video_input_youtube.py
│   │   │   └── __init__.py
│   │   ├── groq
│   │   │   ├── reasoning
│   │   │   │   ├── .gitignore
│   │   │   │   ├── __init__.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── demo_deepseek_qwen.py
│   │   │   │   ├── demo_qwen_2_5_32B.py
│   │   │   │   └── finance_agent.py
│   │   │   ├── __init__.py
│   │   │   ├── agent_team.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── browser_search.py
│   │   │   ├── db.py
│   │   │   ├── deep_knowledge.py
│   │   │   ├── image_agent.py
│   │   │   ├── knowledge.py
│   │   │   ├── metrics.py
│   │   │   ├── README.md
│   │   │   ├── reasoning_agent.py
│   │   │   ├── research_agent_exa.py
│   │   │   ├── research_agent_seltz.py
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   ├── transcription_agent.py
│   │   │   └── translation_agent.py
│   │   ├── huggingface
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── llama_essay_writer.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── ibm
│   │   │   ├── watsonx
│   │   │   │   ├── .gitignore
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── db.py
│   │   │   │   ├── image_agent_bytes.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── README.md
│   │   │   │   ├── structured_output.py
│   │   │   │   └── tool_use.py
│   │   │   ├── __init__.py
│   │   │   └── retry.py
│   │   ├── internlm
│   │   │   └── retry.py
│   │   ├── langdb
│   │   │   ├── __init__.py
│   │   │   ├── agent.py
│   │   │   ├── agent_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── data_analyst.py
│   │   │   ├── finance_agent.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   └── web_search.py
│   │   ├── litellm
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── audio_input_agent.py
│   │   │   ├── basic.py
│   │   │   ├── basic_gpt.py
│   │   │   ├── basic_stream.py
│   │   │   ├── db.py
│   │   │   ├── image_agent.py
│   │   │   ├── image_agent_bytes.py
│   │   │   ├── knowledge.py
│   │   │   ├── memory.py
│   │   │   ├── metrics.py
│   │   │   ├── pdf_input_bytes.py
│   │   │   ├── pdf_input_local.py
│   │   │   ├── pdf_input_url.py
│   │   │   ├── README.md
│   │   │   ├── reasoning_agent.py
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── litellm_openai
│   │   │   ├── __init__.py
│   │   │   ├── audio_input_agent.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   └── tool_use.py
│   │   ├── llama_cpp
│   │   │   ├── __init__.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── lmstudio
│   │   │   ├── __init__.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── db.py
│   │   │   ├── image_agent.py
│   │   │   ├── knowledge.py
│   │   │   ├── memory.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── meta
│   │   │   ├── llama
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_knowledge.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── async_tool_use_stream.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── db.py
│   │   │   │   ├── image_input_bytes.py
│   │   │   │   ├── image_input_file.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── memory.py
│   │   │   │   ├── metrics.py
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── tool_use.py
│   │   │   │   └── tool_use_stream.py
│   │   │   ├── llama_openai
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── async_tool_use_stream.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── image_input_bytes.py
│   │   │   │   ├── image_input_file.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── memory.py
│   │   │   │   ├── metrics.py
│   │   │   │   ├── storage.py
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── tool_use.py
│   │   │   │   └── tool_use_stream.py
│   │   │   ├── __init__.py
│   │   │   ├── README.md
│   │   │   └── retry.py
│   │   ├── mistral
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_structured_output.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── image_bytes_input_agent.py
│   │   │   ├── image_compare_agent.py
│   │   │   ├── image_file_input_agent.py
│   │   │   ├── image_ocr_with_structured_output.py
│   │   │   ├── image_transcribe_document_agent.py
│   │   │   ├── memory.py
│   │   │   ├── mistral_small.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── structured_output_with_tool_use.py
│   │   │   └── tool_use.py
│   │   ├── moonshot
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   └── tool_use.py
│   │   ├── n1n
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   └── tool_use.py
│   │   ├── nebius
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── async_tool_use_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── db.py
│   │   │   ├── knowledge.py
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── nexus
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── async_tool_use_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── nvidia
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── ollama
│   │   │   ├── chat
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── db.py
│   │   │   │   ├── demo_deepseek_r1.py
│   │   │   │   ├── demo_gemma.py
│   │   │   │   ├── demo_phi4.py
│   │   │   │   ├── demo_qwen.py
│   │   │   │   ├── image_agent.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── memory.py
│   │   │   │   ├── ollama_cloud.py
│   │   │   │   ├── reasoning_agent.py
│   │   │   │   ├── retry.py
│   │   │   │   ├── set_client.py
│   │   │   │   ├── set_temperature.py
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── tool_use.py
│   │   │   │   └── tool_use_stream.py
│   │   │   ├── responses
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── tool_use.py
│   │   │   │   └── tool_use_stream.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── openai
│   │   │   ├── chat
│   │   │   │   ├── __init__.py
│   │   │   │   ├── access_memories_in_memory_completed_event.py
│   │   │   │   ├── agent_flex_tier.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_structured_response_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── audio_input_agent.py
│   │   │   │   ├── audio_input_and_output_multi_turn.py
│   │   │   │   ├── audio_input_local_file_upload.py
│   │   │   │   ├── audio_output_agent.py
│   │   │   │   ├── audio_output_stream.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── basic_stream_metrics.py
│   │   │   │   ├── custom_role_map.py
│   │   │   │   ├── db.py
│   │   │   │   ├── generate_images.py
│   │   │   │   ├── image_agent.py
│   │   │   │   ├── image_agent_bytes.py
│   │   │   │   ├── image_agent_with_memory.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── memory.py
│   │   │   │   ├── metrics.py
│   │   │   │   ├── pdf_input_file_upload.py
│   │   │   │   ├── pdf_input_local.py
│   │   │   │   ├── pdf_input_url.py
│   │   │   │   ├── README.md
│   │   │   │   ├── reasoning_o3_mini.py
│   │   │   │   ├── retry.py
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── structured_output_stream.py
│   │   │   │   ├── text_to_speech_agent.py
│   │   │   │   ├── tool_use.py
│   │   │   │   ├── tool_use_stream.py
│   │   │   │   ├── verbosity_control.py
│   │   │   │   └── with_retries.py
│   │   │   ├── responses
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent_flex_tier.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── db.py
│   │   │   │   ├── deep_research_agent.py
│   │   │   │   ├── image_agent.py
│   │   │   │   ├── image_agent_bytes.py
│   │   │   │   ├── image_agent_with_memory.py
│   │   │   │   ├── image_generation_agent.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── memory.py
│   │   │   │   ├── pdf_input_local.py
│   │   │   │   ├── pdf_input_url.py
│   │   │   │   ├── reasoning_o3_mini.py
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── structured_output_with_tools.py
│   │   │   │   ├── tool_use.py
│   │   │   │   ├── tool_use_gpt_5.py
│   │   │   │   ├── tool_use_o3.py
│   │   │   │   ├── tool_use_stream.py
│   │   │   │   ├── verbosity_control.py
│   │   │   │   ├── websearch_builtin_tool.py
│   │   │   │   └── zdr_reasoning_agent.py
│   │   │   └── __init__.py
│   │   ├── openrouter
│   │   │   ├── chat
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── dynamic_model_router.py
│   │   │   │   ├── retry.py
│   │   │   │   ├── structured_output.py
│   │   │   │   └── tool_use.py
│   │   │   ├── responses
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── fallback.py
│   │   │   │   ├── stream.py
│   │   │   │   ├── structured_output.py
│   │   │   │   └── tool_use.py
│   │   │   ├── __init__.py
│   │   │   └── README.md
│   │   ├── perplexity
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── knowledge.py
│   │   │   ├── memory.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   └── web_search.py
│   │   ├── portkey
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── async_tool_use_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── requesty
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   └── tool_use.py
│   │   ├── sambanova
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   └── retry.py
│   │   ├── siliconflow
│   │   │   ├── __init__.py
│   │   │   ├── async_basic_streaming.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   └── tool_use.py
│   │   ├── together
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── image_agent.py
│   │   │   ├── image_agent_bytes.py
│   │   │   ├── image_agent_with_memory.py
│   │   │   ├── README.md
│   │   │   ├── reasoning_agent.py
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── vercel
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── image_agent.py
│   │   │   ├── knowledge.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   └── tool_use.py
│   │   ├── vertexai
│   │   │   ├── claude
│   │   │   │   ├── __init__.py
│   │   │   │   ├── async_basic.py
│   │   │   │   ├── async_basic_stream.py
│   │   │   │   ├── async_tool_use.py
│   │   │   │   ├── basic.py
│   │   │   │   ├── basic_stream.py
│   │   │   │   ├── basic_with_timeout.py
│   │   │   │   ├── betas.py
│   │   │   │   ├── db.py
│   │   │   │   ├── image_input_bytes.py
│   │   │   │   ├── image_input_url.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── memory.py
│   │   │   │   ├── pdf_input_bytes.py
│   │   │   │   ├── pdf_input_local.py
│   │   │   │   ├── prompt_caching.py
│   │   │   │   ├── README.md
│   │   │   │   ├── structured_output.py
│   │   │   │   ├── structured_output_stream.py
│   │   │   │   ├── thinking.py
│   │   │   │   ├── thinking_stream.py
│   │   │   │   ├── tool_use.py
│   │   │   │   └── tool_use_stream.py
│   │   │   ├── __init__.py
│   │   │   └── retry.py
│   │   ├── vllm
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── code_generation.py
│   │   │   ├── db.py
│   │   │   ├── memory.py
│   │   │   ├── README.md
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── xai
│   │   │   ├── __init__.py
│   │   │   ├── async_basic.py
│   │   │   ├── async_basic_stream.py
│   │   │   ├── async_tool_use.py
│   │   │   ├── basic.py
│   │   │   ├── basic_stream.py
│   │   │   ├── finance_agent.py
│   │   │   ├── image_agent.py
│   │   │   ├── image_agent_bytes.py
│   │   │   ├── image_agent_with_memory.py
│   │   │   ├── live_search_agent.py
│   │   │   ├── live_search_agent_stream.py
│   │   │   ├── README.md
│   │   │   ├── reasoning_agent.py
│   │   │   ├── retry.py
│   │   │   ├── structured_output.py
│   │   │   ├── tool_use.py
│   │   │   └── tool_use_stream.py
│   │   ├── .gitignore
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 91_tools
│   │   ├── async
│   │   │   ├── __init__.py
│   │   │   ├── groq-demo.py
│   │   │   └── openai-demo.py
│   │   ├── exceptions
│   │   │   ├── retry_tool_call.py
│   │   │   ├── retry_tool_call_from_post_hook.py
│   │   │   └── stop_agent_exception.py
│   │   ├── mcp
│   │   │   ├── dynamic_headers
│   │   │   │   ├── client.py
│   │   │   │   └── server.py
│   │   │   ├── local_server
│   │   │   │   ├── client.py
│   │   │   │   └── server.py
│   │   │   ├── mcp_toolbox_demo
│   │   │   │   ├── config
│   │   │   │   ├── agent.py
│   │   │   │   ├── agent_os.py
│   │   │   │   ├── docker-compose.yml
│   │   │   │   ├── hotel_management_typesafe.py
│   │   │   │   ├── hotel_management_workflows.py
│   │   │   │   ├── pyproject.toml
│   │   │   │   ├── README.md
│   │   │   │   ├── requirements.txt
│   │   │   │   └── uv.lock
│   │   │   ├── sse_transport
│   │   │   │   ├── client.py
│   │   │   │   ├── README.md
│   │   │   │   └── server.py
│   │   │   ├── streamable_http_transport
│   │   │   │   ├── client.py
│   │   │   │   ├── README.md
│   │   │   │   └── server.py
│   │   │   ├── __init__.py
│   │   │   ├── agno_mcp.py
│   │   │   ├── airbnb.py
│   │   │   ├── brave.py
│   │   │   ├── cli.py
│   │   │   ├── filesystem.py
│   │   │   ├── gibsonai.py
│   │   │   ├── github.py
│   │   │   ├── graphiti.py
│   │   │   ├── groq_mcp.py
│   │   │   ├── include_exclude_tools.py
│   │   │   ├── include_tools.py
│   │   │   ├── mcp_toolbox_for_db.py
│   │   │   ├── mem0.py
│   │   │   ├── multiple_servers.py
│   │   │   ├── multiple_servers_allow_partial_failure.py
│   │   │   ├── notion_mcp_agent.py
│   │   │   ├── oxylabs.py
│   │   │   ├── parallel.py
│   │   │   ├── pipedream_auth.py
│   │   │   ├── pipedream_google_calendar.py
│   │   │   ├── pipedream_linkedin.py
│   │   │   ├── pipedream_slack.py
│   │   │   ├── qdrant.py
│   │   │   ├── README.md
│   │   │   ├── sequential_thinking.py
│   │   │   ├── stagehand.py
│   │   │   ├── stripe.py
│   │   │   ├── supabase.py
│   │   │   └── tool_name_prefix.py
│   │   ├── models
│   │   │   ├── __init__.py
│   │   │   ├── azure_openai_tools.py
│   │   │   ├── gemini_image_generation.py
│   │   │   ├── gemini_video_generation.py
│   │   │   ├── morph.py
│   │   │   ├── nebius_tools.py
│   │   │   └── openai_tools.py
│   │   ├── other
│   │   │   ├── __init__.py
│   │   │   ├── add_tool_after_initialization.py
│   │   │   ├── cache_tool_calls.py
│   │   │   ├── complex_input_types.py
│   │   │   ├── human_in_the_loop.py
│   │   │   ├── include_exclude_tools.py
│   │   │   ├── include_exclude_tools_custom_toolkit.py
│   │   │   ├── session_state_tool.py
│   │   │   ├── stop_after_tool_call.py
│   │   │   ├── stop_after_tool_call_dual_inheritance.py
│   │   │   └── stop_after_tool_call_in_toolkit.py
│   │   ├── tool_decorator
│   │   │   ├── async_tool_decorator.py
│   │   │   ├── cache_tool_calls.py
│   │   │   ├── stop_after_tool_call.py
│   │   │   ├── tool_decorator.py
│   │   │   ├── tool_decorator_async.py
│   │   │   ├── tool_decorator_on_class_method.py
│   │   │   ├── tool_decorator_with_hook.py
│   │   │   └── tool_decorator_with_instructions.py
│   │   ├── tool_hooks
│   │   │   ├── async_pre_and_post_hooks.py
│   │   │   ├── pre_and_post_hooks.py
│   │   │   ├── tool_hook.py
│   │   │   ├── tool_hook_async.py
│   │   │   ├── tool_hook_in_toolkit.py
│   │   │   ├── tool_hook_in_toolkit_async.py
│   │   │   ├── tool_hook_in_toolkit_with_state.py
│   │   │   ├── tool_hook_in_toolkit_with_state_nested.py
│   │   │   ├── tool_hooks_in_toolkit_nested.py
│   │   │   └── tool_hooks_in_toolkit_nested_async.py
│   │   ├── __init__.py
│   │   ├── agentql_tools.py
│   │   ├── airflow_tools.py
│   │   ├── apify_tools.py
│   │   ├── arxiv_tools.py
│   │   ├── aws_lambda_tools.py
│   │   ├── aws_ses_tools.py
│   │   ├── baidusearch_tools.py
│   │   ├── bitbucket_tools.py
│   │   ├── brandfetch_tools.py
│   │   ├── bravesearch_tools.py
│   │   ├── brightdata_tools.py
│   │   ├── browserbase_tools.py
│   │   ├── calcom_tools.py
│   │   ├── calculator_tools.py
│   │   ├── cartesia_tools.py
│   │   ├── CLAUDE.md
│   │   ├── clickup_tools.py
│   │   ├── composio_tools.py
│   │   ├── confluence_tools.py
│   │   ├── crawl4ai_tools.py
│   │   ├── csv_tools.py
│   │   ├── custom_api_tools.py
│   │   ├── custom_async_tools.py
│   │   ├── custom_tool_events.py
│   │   ├── custom_tools.py
│   │   ├── dalle_tools.py
│   │   ├── daytona_tools.py
│   │   ├── desi_vocal_tools.py
│   │   ├── discord_tools.py
│   │   ├── docker_tools.py
│   │   ├── duckdb_tools.py
│   │   ├── duckduckgo_tools.py
│   │   ├── e2b_tools.py
│   │   ├── elevenlabs_tools.py
│   │   ├── email_tools.py
│   │   ├── evm_tools.py
│   │   ├── exa_tools.py
│   │   ├── fal_tools.py
│   │   ├── file_generation_tools.py
│   │   ├── file_tools.py
│   │   ├── financial_datasets_tools.py
│   │   ├── firecrawl_tools.py
│   │   ├── giphy_tools.py
│   │   ├── github_tools.py
│   │   ├── gmail_tools.py
│   │   ├── google_bigquery_tools.py
│   │   ├── google_drive.py
│   │   ├── google_maps_tools.py
│   │   ├── googlecalendar_tools.py
│   │   ├── googlesheets_tools.py
│   │   ├── hackernews_tools.py
│   │   ├── imdb.csv
│   │   ├── jinareader_tools.py
│   │   ├── jira_tools.py
│   │   ├── knowledge_tool.py
│   │   ├── linear_tools.py
│   │   ├── linkup_tools.py
│   │   ├── lumalabs_tools.py
│   │   ├── mcp_tools.py
│   │   ├── mem0_tools.py
│   │   ├── mlx_transcribe_tools.py
│   │   ├── models_lab_tools.py
│   │   ├── moviepy_video_tools.py
│   │   ├── multiple_tools.py
│   │   ├── nano_banana_tools.py
│   │   ├── neo4j_tools.py
│   │   ├── newspaper4k_tools.py
│   │   ├── newspaper_tools.py
│   │   ├── notion_tools.py
│   │   ├── openbb_tools.py
│   │   ├── opencv_tools.py
│   │   ├── openweather_tools.py
│   │   ├── oxylabs_tools.py
│   │   ├── pandas_tools.py
│   │   ├── parallel_tools.py
│   │   ├── postgres_tools.py
│   │   ├── pubmed_tools.py
│   │   ├── python_function_as_tool.py
│   │   ├── python_tools.py
│   │   ├── README.md
│   │   ├── reddit_tools.py
│   │   ├── redshift_tools.py
│   │   ├── replicate_tools.py
│   │   ├── resend_tools.py
│   │   ├── scrapegraph_tools.py
│   │   ├── searxng_tools.py
│   │   ├── seltz_tools.py
│   │   ├── serpapi_tools.py
│   │   ├── serper_tools.py
│   │   ├── shell_tools.py
│   │   ├── shopify_tools.py
│   │   ├── slack_tools.py
│   │   ├── sleep_tools.py
│   │   ├── spider_tools.py
│   │   ├── spotify_tools.py
│   │   ├── sql_tools.py
│   │   ├── tavily_tools.py
│   │   ├── telegram_tools.py
│   │   ├── todoist_tools.py
│   │   ├── tool_calls_accesing_agent.py
│   │   ├── trafilatura_tools.py
│   │   ├── trello_tools.py
│   │   ├── twilio_tools.py
│   │   ├── unsplash_tools.py
│   │   ├── valyu_tools.py
│   │   ├── visualization_tools.py
│   │   ├── web_tools.py
│   │   ├── webbrowser_tools.py
│   │   ├── webex_tools.py
│   │   ├── websearch_tools.py
│   │   ├── website_tools.py
│   │   ├── website_tools_knowledge.py
│   │   ├── whatsapp_tools.py
│   │   ├── wikipedia_tools.py
│   │   ├── x_tools.py
│   │   ├── yfinance_tools.py
│   │   ├── youtube_tools.py
│   │   ├── zendesk_tools.py
│   │   ├── zep_async_tools.py
│   │   ├── zep_tools.py
│   │   └── zoom_tools.py
│   ├── 92_integrations
│   │   ├── a2a
│   │   │   ├── basic_agent
│   │   │   │   ├── __init__.py
│   │   │   │   ├── __main__.py
│   │   │   │   ├── basic_agent.py
│   │   │   │   ├── client.py
│   │   │   │   └── README.md
│   │   │   └── __init__.py
│   │   ├── discord
│   │   │   ├── __init__.py
│   │   │   ├── agent_with_media.py
│   │   │   ├── agent_with_user_memory.py
│   │   │   ├── basic.py
│   │   │   └── README.md
│   │   ├── memory
│   │   │   ├── __init__.py
│   │   │   ├── mem0_integration.py
│   │   │   ├── memori_integration.py
│   │   │   └── zep_integration.py
│   │   ├── observability
│   │   │   ├── teams
│   │   │   │   ├── __init__.py
│   │   │   │   ├── langfuse_via_openinference_async_team.py
│   │   │   │   └── langfuse_via_openinference_team.py
│   │   │   ├── workflows
│   │   │   │   ├── arize_phoenix_via_openinference_workflow.py
│   │   │   │   └── langfuse_via_openinference_workfows.py
│   │   │   ├── __init__.py
│   │   │   ├── agent_ops.py
│   │   │   ├── arize_phoenix_moving_traces_to_different_projects.py
│   │   │   ├── arize_phoenix_via_openinference.py
│   │   │   ├── arize_phoenix_via_openinference_local.py
│   │   │   ├── atla_op.py
│   │   │   ├── langfuse_via_openinference.py
│   │   │   ├── langfuse_via_openinference_response_model.py
│   │   │   ├── langfuse_via_openlit.py
│   │   │   ├── langsmith_via_openinference.py
│   │   │   ├── langtrace_op.py
│   │   │   ├── langwatch_op.py
│   │   │   ├── logfire_via_openinference.py
│   │   │   ├── maxim_ops.py
│   │   │   ├── opik_via_openinference.py
│   │   │   ├── README.md
│   │   │   ├── trace_to_database.py
│   │   │   ├── traceloop_op.py
│   │   │   └── weave_op.py
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   └── README.md
│   ├── 93_components
│   │   ├── __init__.py
│   │   ├── agent_os_registry.py
│   │   ├── demo.py
│   │   ├── get_agent.py
│   │   ├── get_team.py
│   │   ├── get_workflow.py
│   │   ├── README.md
│   │   ├── registry.py
│   │   ├── save_agent.py
│   │   ├── save_team.py
│   │   └── save_workflow.py
│   ├── demo
│   │   ├── agents
│   │   │   ├── __init__.py
│   │   │   ├── db.py
│   │   │   ├── deep_knowledge_agent.py
│   │   │   ├── devil_advocate_agent.py
│   │   │   ├── finance_agent.py
│   │   │   ├── knowledge_agent.py
│   │   │   ├── mcp_agent.py
│   │   │   ├── pal_agent.py
│   │   │   ├── report_writer_agent.py
│   │   │   ├── research_agent.py
│   │   │   └── web_intelligence_agent.py
│   │   ├── teams
│   │   │   ├── __init__.py
│   │   │   ├── db.py
│   │   │   ├── due_diligence_team.py
│   │   │   └── investment_team.py
│   │   ├── workflows
│   │   │   ├── __init__.py
│   │   │   ├── db.py
│   │   │   ├── deep_research_workflow.py
│   │   │   └── startup_analyst_workflow.py
│   │   ├── .gitignore
│   │   ├── __init__.py
│   │   ├── CLAUDE.md
│   │   ├── config.yaml
│   │   ├── db.py
│   │   ├── README.md
│   │   ├── registry.py
│   │   ├── requirements.in
│   │   ├── run.py
│   │   ├── SAMPLE_QUERIES.md
│   │   └── TEST_LOG.md
│   ├── scripts
│   │   ├── __init__.py
│   │   ├── _utils.sh
│   │   ├── cookbook_runner.py
│   │   ├── format.bat
│   │   ├── format.sh
│   │   ├── run_cassandra.bat
│   │   ├── run_cassandra.sh
│   │   ├── run_clickhouse.bat
│   │   ├── run_clickhouse.sh
│   │   ├── run_couchbase.bat
│   │   ├── run_couchbase.sh
│   │   ├── run_mongodb.bat
│   │   ├── run_mongodb.sh
│   │   ├── run_mysql.bat
│   │   ├── run_mysql.sh
│   │   ├── run_pgvector.bat
│   │   ├── run_pgvector.sh
│   │   ├── run_qdrant.bat
│   │   ├── run_qdrant.sh
│   │   ├── run_redis.bat
│   │   ├── run_redis.sh
│   │   ├── run_singlestore.bat
│   │   ├── run_singlestore.sh
│   │   ├── run_surrealdb.bat
│   │   ├── run_surrealdb.sh
│   │   ├── run_weaviate.bat
│   │   ├── run_weaviate.sh
│   │   ├── validate.bat
│   │   └── validate.sh
│   ├── .gitignore
│   ├── __init__.py
│   ├── mypy.ini
│   └── README.md
├── libs
│   ├── agno
│   │   ├── agno
│   │   │   ├── agent
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   └── remote.py
│   │   │   ├── api
│   │   │   │   ├── schemas
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── api.py
│   │   │   │   ├── evals.py
│   │   │   │   ├── os.py
│   │   │   │   ├── routes.py
│   │   │   │   ├── settings.py
│   │   │   │   ├── team.py
│   │   │   │   └── workflow.py
│   │   │   ├── client
│   │   │   │   ├── a2a
│   │   │   │   ├── __init__.py
│   │   │   │   └── os.py
│   │   │   ├── cloud
│   │   │   │   └── aws
│   │   │   ├── compression
│   │   │   │   ├── __init__.py
│   │   │   │   └── manager.py
│   │   │   ├── culture
│   │   │   │   ├── __init__.py
│   │   │   │   └── manager.py
│   │   │   ├── db
│   │   │   │   ├── async_postgres
│   │   │   │   ├── dynamo
│   │   │   │   ├── firestore
│   │   │   │   ├── gcs_json
│   │   │   │   ├── in_memory
│   │   │   │   ├── json
│   │   │   │   ├── migrations
│   │   │   │   ├── mongo
│   │   │   │   ├── mysql
│   │   │   │   ├── postgres
│   │   │   │   ├── redis
│   │   │   │   ├── schemas
│   │   │   │   ├── singlestore
│   │   │   │   ├── sqlite
│   │   │   │   ├── surrealdb
│   │   │   │   ├── __init__.py
│   │   │   │   ├── base.py
│   │   │   │   └── utils.py
│   │   │   ├── eval
│   │   │   │   ├── __init__.py
│   │   │   │   ├── accuracy.py
│   │   │   │   ├── agent_as_judge.py
│   │   │   │   ├── base.py
│   │   │   │   ├── performance.py
│   │   │   │   ├── reliability.py
│   │   │   │   └── utils.py
│   │   │   ├── guardrails
│   │   │   │   ├── __init__.py
│   │   │   │   ├── base.py
│   │   │   │   ├── openai.py
│   │   │   │   ├── pii.py
│   │   │   │   └── prompt_injection.py
│   │   │   ├── hooks
│   │   │   │   ├── __init__.py
│   │   │   │   └── decorator.py
│   │   │   ├── integrations
│   │   │   │   ├── discord
│   │   │   │   └── __init__.py
│   │   │   ├── knowledge
│   │   │   │   ├── chunking
│   │   │   │   ├── document
│   │   │   │   ├── embedder
│   │   │   │   ├── reader
│   │   │   │   ├── remote_content
│   │   │   │   ├── reranker
│   │   │   │   ├── __init__.py
│   │   │   │   ├── content.py
│   │   │   │   ├── filesystem.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── protocol.py
│   │   │   │   ├── types.py
│   │   │   │   └── utils.py
│   │   │   ├── learn
│   │   │   │   ├── stores
│   │   │   │   ├── __init__.py
│   │   │   │   ├── config.py
│   │   │   │   ├── curate.py
│   │   │   │   ├── machine.py
│   │   │   │   ├── schemas.py
│   │   │   │   └── utils.py
│   │   │   ├── memory
│   │   │   │   ├── strategies
│   │   │   │   ├── __init__.py
│   │   │   │   └── manager.py
│   │   │   ├── models
│   │   │   │   ├── aimlapi
│   │   │   │   ├── anthropic
│   │   │   │   ├── aws
│   │   │   │   ├── azure
│   │   │   │   ├── cerebras
│   │   │   │   ├── cohere
│   │   │   │   ├── cometapi
│   │   │   │   ├── dashscope
│   │   │   │   ├── deepinfra
│   │   │   │   ├── deepseek
│   │   │   │   ├── fireworks
│   │   │   │   ├── google
│   │   │   │   ├── groq
│   │   │   │   ├── huggingface
│   │   │   │   ├── ibm
│   │   │   │   ├── internlm
│   │   │   │   ├── langdb
│   │   │   │   ├── litellm
│   │   │   │   ├── llama_cpp
│   │   │   │   ├── lmstudio
│   │   │   │   ├── meta
│   │   │   │   ├── mistral
│   │   │   │   ├── moonshot
│   │   │   │   ├── n1n
│   │   │   │   ├── nebius
│   │   │   │   ├── nexus
│   │   │   │   ├── nvidia
│   │   │   │   ├── ollama
│   │   │   │   ├── openai
│   │   │   │   ├── openrouter
│   │   │   │   ├── perplexity
│   │   │   │   ├── portkey
│   │   │   │   ├── requesty
│   │   │   │   ├── sambanova
│   │   │   │   ├── siliconflow
│   │   │   │   ├── together
│   │   │   │   ├── vercel
│   │   │   │   ├── vertexai
│   │   │   │   ├── vllm
│   │   │   │   ├── xai
│   │   │   │   ├── __init__.py
│   │   │   │   ├── base.py
│   │   │   │   ├── defaults.py
│   │   │   │   ├── message.py
│   │   │   │   ├── metrics.py
│   │   │   │   ├── response.py
│   │   │   │   └── utils.py
│   │   │   ├── os
│   │   │   │   ├── interfaces
│   │   │   │   ├── middleware
│   │   │   │   ├── routers
│   │   │   │   ├── __init__.py
│   │   │   │   ├── app.py
│   │   │   │   ├── auth.py
│   │   │   │   ├── config.py
│   │   │   │   ├── managers.py
│   │   │   │   ├── mcp.py
│   │   │   │   ├── router.py
│   │   │   │   ├── schema.py
│   │   │   │   ├── scopes.py
│   │   │   │   ├── settings.py
│   │   │   │   └── utils.py
│   │   │   ├── reasoning
│   │   │   │   ├── __init__.py
│   │   │   │   ├── anthropic.py
│   │   │   │   ├── azure_ai_foundry.py
│   │   │   │   ├── deepseek.py
│   │   │   │   ├── default.py
│   │   │   │   ├── gemini.py
│   │   │   │   ├── groq.py
│   │   │   │   ├── helpers.py
│   │   │   │   ├── manager.py
│   │   │   │   ├── ollama.py
│   │   │   │   ├── openai.py
│   │   │   │   ├── step.py
│   │   │   │   └── vertexai.py
│   │   │   ├── registry
│   │   │   │   ├── __init__.py
│   │   │   │   └── registry.py
│   │   │   ├── remote
│   │   │   │   ├── __init__.py
│   │   │   │   └── base.py
│   │   │   ├── run
│   │   │   │   ├── cancellation_management
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── base.py
│   │   │   │   ├── cancel.py
│   │   │   │   ├── messages.py
│   │   │   │   ├── requirement.py
│   │   │   │   ├── team.py
│   │   │   │   └── workflow.py
│   │   │   ├── session
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── summary.py
│   │   │   │   ├── team.py
│   │   │   │   └── workflow.py
│   │   │   ├── skills
│   │   │   │   ├── loaders
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent_skills.py
│   │   │   │   ├── errors.py
│   │   │   │   ├── skill.py
│   │   │   │   ├── utils.py
│   │   │   │   └── validator.py
│   │   │   ├── team
│   │   │   │   ├── __init__.py
│   │   │   │   ├── remote.py
│   │   │   │   └── team.py
│   │   │   ├── tools
│   │   │   │   ├── mcp
│   │   │   │   ├── models
│   │   │   │   ├── streamlit
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agentql.py
│   │   │   │   ├── airflow.py
│   │   │   │   ├── api.py
│   │   │   │   ├── apify.py
│   │   │   │   ├── arxiv.py
│   │   │   │   ├── aws_lambda.py
│   │   │   │   ├── aws_ses.py
│   │   │   │   ├── baidusearch.py
│   │   │   │   ├── bitbucket.py
│   │   │   │   ├── brandfetch.py
│   │   │   │   ├── bravesearch.py
│   │   │   │   ├── brightdata.py
│   │   │   │   ├── browserbase.py
│   │   │   │   ├── calcom.py
│   │   │   │   ├── calculator.py
│   │   │   │   ├── cartesia.py
│   │   │   │   ├── clickup.py
│   │   │   │   ├── confluence.py
│   │   │   │   ├── crawl4ai.py
│   │   │   │   ├── csv_toolkit.py
│   │   │   │   ├── dalle.py
│   │   │   │   ├── daytona.py
│   │   │   │   ├── decorator.py
│   │   │   │   ├── desi_vocal.py
│   │   │   │   ├── discord.py
│   │   │   │   ├── docker.py
│   │   │   │   ├── duckdb.py
│   │   │   │   ├── duckduckgo.py
│   │   │   │   ├── e2b.py
│   │   │   │   ├── eleven_labs.py
│   │   │   │   ├── email.py
│   │   │   │   ├── evm.py
│   │   │   │   ├── exa.py
│   │   │   │   ├── fal.py
│   │   │   │   ├── file.py
│   │   │   │   ├── file_generation.py
│   │   │   │   ├── financial_datasets.py
│   │   │   │   ├── firecrawl.py
│   │   │   │   ├── function.py
│   │   │   │   ├── giphy.py
│   │   │   │   ├── github.py
│   │   │   │   ├── gmail.py
│   │   │   │   ├── google_bigquery.py
│   │   │   │   ├── google_drive.py
│   │   │   │   ├── google_maps.py
│   │   │   │   ├── googlecalendar.py
│   │   │   │   ├── googlesheets.py
│   │   │   │   ├── hackernews.py
│   │   │   │   ├── jina.py
│   │   │   │   ├── jira.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── linear.py
│   │   │   │   ├── linkup.py
│   │   │   │   ├── local_file_system.py
│   │   │   │   ├── lumalab.py
│   │   │   │   ├── mcp_toolbox.py
│   │   │   │   ├── mem0.py
│   │   │   │   ├── memory.py
│   │   │   │   ├── mlx_transcribe.py
│   │   │   │   ├── models_labs.py
│   │   │   │   ├── moviepy_video.py
│   │   │   │   ├── nano_banana.py
│   │   │   │   ├── neo4j.py
│   │   │   │   ├── newspaper.py
│   │   │   │   ├── newspaper4k.py
│   │   │   │   ├── notion.py
│   │   │   │   ├── openai.py
│   │   │   │   ├── openbb.py
│   │   │   │   ├── opencv.py
│   │   │   │   ├── openweather.py
│   │   │   │   ├── oxylabs.py
│   │   │   │   ├── pandas.py
│   │   │   │   ├── parallel.py
│   │   │   │   ├── postgres.py
│   │   │   │   ├── pubmed.py
│   │   │   │   ├── python.py
│   │   │   │   ├── reasoning.py
│   │   │   │   ├── reddit.py
│   │   │   │   ├── redshift.py
│   │   │   │   ├── replicate.py
│   │   │   │   ├── resend.py
│   │   │   │   ├── scrapegraph.py
│   │   │   │   ├── searxng.py
│   │   │   │   ├── seltz.py
│   │   │   │   ├── serpapi.py
│   │   │   │   ├── serper.py
│   │   │   │   ├── shell.py
│   │   │   │   ├── shopify.py
│   │   │   │   ├── slack.py
│   │   │   │   ├── sleep.py
│   │   │   │   ├── spider.py
│   │   │   │   ├── spotify.py
│   │   │   │   ├── sql.py
│   │   │   │   ├── tavily.py
│   │   │   │   ├── telegram.py
│   │   │   │   ├── todoist.py
│   │   │   │   ├── tool_registry.py
│   │   │   │   ├── toolkit.py
│   │   │   │   ├── trafilatura.py
│   │   │   │   ├── trello.py
│   │   │   │   ├── twilio.py
│   │   │   │   ├── unsplash.py
│   │   │   │   ├── user_control_flow.py
│   │   │   │   ├── valyu.py
│   │   │   │   ├── visualization.py
│   │   │   │   ├── webbrowser.py
│   │   │   │   ├── webex.py
│   │   │   │   ├── websearch.py
│   │   │   │   ├── website.py
│   │   │   │   ├── webtools.py
│   │   │   │   ├── whatsapp.py
│   │   │   │   ├── wikipedia.py
│   │   │   │   ├── workflow.py
│   │   │   │   ├── x.py
│   │   │   │   ├── yfinance.py
│   │   │   │   ├── youtube.py
│   │   │   │   ├── zendesk.py
│   │   │   │   ├── zep.py
│   │   │   │   └── zoom.py
│   │   │   ├── tracing
│   │   │   │   ├── __init__.py
│   │   │   │   ├── exporter.py
│   │   │   │   ├── schemas.py
│   │   │   │   └── setup.py
│   │   │   ├── utils
│   │   │   │   ├── models
│   │   │   │   ├── print_response
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── audio.py
│   │   │   │   ├── certs.py
│   │   │   │   ├── code_execution.py
│   │   │   │   ├── common.py
│   │   │   │   ├── cryptography.py
│   │   │   │   ├── dttm.py
│   │   │   │   ├── enum.py
│   │   │   │   ├── env.py
│   │   │   │   ├── events.py
│   │   │   │   ├── format_str.py
│   │   │   │   ├── functions.py
│   │   │   │   ├── gemini.py
│   │   │   │   ├── hooks.py
│   │   │   │   ├── http.py
│   │   │   │   ├── json_schema.py
│   │   │   │   ├── knowledge.py
│   │   │   │   ├── location.py
│   │   │   │   ├── log.py
│   │   │   │   ├── mcp.py
│   │   │   │   ├── media.py
│   │   │   │   ├── merge_dict.py
│   │   │   │   ├── message.py
│   │   │   │   ├── openai.py
│   │   │   │   ├── os.py
│   │   │   │   ├── pickle.py
│   │   │   │   ├── pprint.py
│   │   │   │   ├── prompts.py
│   │   │   │   ├── reasoning.py
│   │   │   │   ├── remote.py
│   │   │   │   ├── response.py
│   │   │   │   ├── response_iterator.py
│   │   │   │   ├── safe_formatter.py
│   │   │   │   ├── serialize.py
│   │   │   │   ├── shell.py
│   │   │   │   ├── streamlit.py
│   │   │   │   ├── string.py
│   │   │   │   ├── team.py
│   │   │   │   ├── timer.py
│   │   │   │   ├── tokens.py
│   │   │   │   ├── tools.py
│   │   │   │   ├── web.py
│   │   │   │   ├── whatsapp.py
│   │   │   │   └── yaml_io.py
│   │   │   ├── vectordb
│   │   │   │   ├── cassandra
│   │   │   │   ├── chroma
│   │   │   │   ├── clickhouse
│   │   │   │   ├── couchbase
│   │   │   │   ├── lancedb
│   │   │   │   ├── langchaindb
│   │   │   │   ├── lightrag
│   │   │   │   ├── llamaindex
│   │   │   │   ├── milvus
│   │   │   │   ├── mongodb
│   │   │   │   ├── pgvector
│   │   │   │   ├── pineconedb
│   │   │   │   ├── qdrant
│   │   │   │   ├── redis
│   │   │   │   ├── singlestore
│   │   │   │   ├── surrealdb
│   │   │   │   ├── upstashdb
│   │   │   │   ├── weaviate
│   │   │   │   ├── __init__.py
│   │   │   │   ├── base.py
│   │   │   │   ├── distance.py
│   │   │   │   └── search.py
│   │   │   ├── workflow
│   │   │   │   ├── __init__.py
│   │   │   │   ├── agent.py
│   │   │   │   ├── condition.py
│   │   │   │   ├── loop.py
│   │   │   │   ├── parallel.py
│   │   │   │   ├── remote.py
│   │   │   │   ├── router.py
│   │   │   │   ├── step.py
│   │   │   │   ├── steps.py
│   │   │   │   ├── types.py
│   │   │   │   └── workflow.py
│   │   │   ├── __init__.py
│   │   │   ├── debug.py
│   │   │   ├── exceptions.py
│   │   │   ├── filters.py
│   │   │   ├── media.py
│   │   │   ├── py.typed
│   │   │   └── table.py
│   │   ├── migrations
│   │   │   ├── v1_to_v2
│   │   │   │   ├── migrate_to_v2.py
│   │   │   │   └── migrate_vectordbs_to_v2.py
│   │   │   ├── migrate_mysql.py
│   │   │   ├── migrate_postgres.py
│   │   │   ├── migrate_singlestore.py
│   │   │   ├── migrate_sqlite.py
│   │   │   └── README.md
│   │   ├── scripts
│   │   │   ├── _utils.sh
│   │   │   ├── format.bat
│   │   │   ├── format.sh
│   │   │   ├── generate_requirements.sh
│   │   │   ├── release_manual.sh
│   │   │   ├── test.bat
│   │   │   ├── test.sh
│   │   │   ├── validate.bat
│   │   │   └── validate.sh
│   │   ├── tests
│   │   │   ├── integration
│   │   │   │   ├── agent
│   │   │   │   ├── db
│   │   │   │   ├── embedder
│   │   │   │   ├── knowledge
│   │   │   │   ├── managers
│   │   │   │   ├── models
│   │   │   │   ├── os
│   │   │   │   ├── reranker
│   │   │   │   ├── res
│   │   │   │   ├── session
│   │   │   │   ├── teams
│   │   │   │   ├── tools
│   │   │   │   ├── vector_dbs
│   │   │   │   ├── workflows
│   │   │   │   ├── __init__.py
│   │   │   │   ├── conftest.py
│   │   │   │   ├── test_basic.py
│   │   │   │   └── test_os_basic.py
│   │   │   ├── system
│   │   │   │   ├── tests
│   │   │   │   ├── __init__.py
│   │   │   │   ├── adk_server.py
│   │   │   │   ├── agno_a2a_server.py
│   │   │   │   ├── docker-compose.yaml
│   │   │   │   ├── Dockerfile.adk
│   │   │   │   ├── Dockerfile.agno_a2a
│   │   │   │   ├── Dockerfile.gateway
│   │   │   │   ├── Dockerfile.remote
│   │   │   │   ├── gateway_server.py
│   │   │   │   ├── pytest.ini
│   │   │   │   ├── README.md
│   │   │   │   ├── remote_server.py
│   │   │   │   ├── requirements.txt
│   │   │   │   └── run_tests.sh
│   │   │   ├── unit
│   │   │   │   ├── a2a
│   │   │   │   ├── agent
│   │   │   │   ├── app
│   │   │   │   ├── compression
│   │   │   │   ├── db
│   │   │   │   ├── eval
│   │   │   │   ├── integrations
│   │   │   │   ├── knowledge
│   │   │   │   ├── memory
│   │   │   │   ├── models
│   │   │   │   ├── os
│   │   │   │   ├── reader
│   │   │   │   ├── reasoning
│   │   │   │   ├── registry
│   │   │   │   ├── run
│   │   │   │   ├── skills
│   │   │   │   ├── team
│   │   │   │   ├── telemetry
│   │   │   │   ├── tools
│   │   │   │   ├── utils
│   │   │   │   ├── vectordb
│   │   │   │   ├── workflow
│   │   │   │   ├── __init__.py
│   │   │   │   ├── response.py
│   │   │   │   └── test_filters.py
│   │   │   └── __init__.py
│   │   ├── LICENSE
│   │   ├── pyproject.toml
│   │   └── requirements.txt
│   └── agno_infra
│       ├── agno
│       │   ├── aws
│       │   │   ├── app
│       │   │   ├── resource
│       │   │   ├── __init__.py
│       │   │   ├── api_client.py
│       │   │   ├── context.py
│       │   │   └── resources.py
│       │   ├── base
│       │   │   ├── __init__.py
│       │   │   ├── app.py
│       │   │   ├── base.py
│       │   │   ├── context.py
│       │   │   ├── db_app.py
│       │   │   ├── resource.py
│       │   │   └── resources.py
│       │   ├── cli
│       │   │   ├── __init__.py
│       │   │   ├── config.py
│       │   │   ├── console.py
│       │   │   ├── entrypoint.py
│       │   │   ├── infra_cli.py
│       │   │   ├── operator.py
│       │   │   ├── settings.py
│       │   │   └── utils.py
│       │   ├── docker
│       │   │   ├── app
│       │   │   ├── resource
│       │   │   ├── __init__.py
│       │   │   ├── api_client.py
│       │   │   ├── context.py
│       │   │   └── resources.py
│       │   ├── infra
│       │   │   ├── __init__.py
│       │   │   ├── config.py
│       │   │   ├── enums.py
│       │   │   ├── helpers.py
│       │   │   ├── operator.py
│       │   │   └── settings.py
│       │   ├── utilities
│       │   │   ├── __init__.py
│       │   │   ├── defaults.py
│       │   │   ├── filesystem.py
│       │   │   ├── git.py
│       │   │   ├── json_io.py
│       │   │   ├── load_env.py
│       │   │   ├── logging.py
│       │   │   ├── py_io.py
│       │   │   ├── pyproject.py
│       │   │   ├── resource_filter.py
│       │   │   ├── string.py
│       │   │   └── yaml_io.py
│       │   ├── __init__.py
│       │   ├── constants.py
│       │   └── py.typed
│       ├── scripts
│       │   ├── _utils.sh
│       │   ├── format.bat
│       │   ├── format.sh
│       │   ├── generate_requirements.sh
│       │   ├── release_manual.sh
│       │   ├── test.sh
│       │   ├── validate.bat
│       │   └── validate.sh
│       ├── tests
│       │   └── __init__.py
│       ├── LICENSE
│       ├── pyproject.toml
│       ├── README.md
│       └── requirements.txt
├── scripts
│   ├── _utils.bat
│   ├── _utils.sh
│   ├── cookbook_setup.sh
│   ├── demo_setup.bat
│   ├── demo_setup.ps1
│   ├── demo_setup.sh
│   ├── dev_setup.bat
│   ├── dev_setup.ps1
│   ├── dev_setup.sh
│   ├── format.bat
│   ├── format.sh
│   ├── perf_setup.sh
│   ├── run_model_tests.sh
│   ├── test.bat
│   ├── test.sh
│   ├── test_setup.bat
│   ├── test_setup.sh
│   ├── validate.bat
│   └── validate.sh
├── .cursorrules
├── .editorconfig
├── .gitignore
├── CLAUDE.md
├── CODE_OF_CONDUCT.md
├── CODEOWNERS
├── CONTRIBUTING.md
├── LICENSE
└── README.md
