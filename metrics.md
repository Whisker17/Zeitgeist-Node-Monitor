# Metrics

Zeitgeist can currently support a large amount of data information monitoring. The current template selects some of the more commonly used ones. If you need to customize it yourself, you can refer to the following metrics to modify.

| Metrics                                                      | Info                                                         | Type      | Status |
| ------------------------------------------------------------ | ------------------------------------------------------------ | --------- | ------ |
| polkadot_authority_discovery_amount_external_addresses_last_published | Number of external addresses published when authority discovery last published addresses. | gauge     |        |
| polkadot_authority_discovery_authority_address_requests_pending | Number of pending authority address requests.                | gauge     |        |
| polkadot_authority_discovery_authority_addresses_requested_total | Number of times authority discovery has requested external addresses of a single authority. | counter   |        |
| polkadot_authority_discovery_dht_event_received              | Number of dht events received by authority discovery.        | counter   |        |
| polkadot_authority_discovery_handle_value_found_event_failure | Number of times handling a dht value found event failed.     | counter   |        |
| polkadot_authority_discovery_known_authorities_count         | Number of authorities known by authority discovery.          | gauge     |        |
| polkadot_authority_discovery_times_published_total           | Number of times authority discovery has published external addresses. | counter   |        |
| polkadot_block_height                                        | Block height info of the chain                               | gauge     |        |
| polkadot_block_verification_and_import_time_bucket           | Time taken to verify and import blocks                       | histogram |        |
| polkadot_block_verification_and_import_time_sum              |                                                              |           |        |
| polkadot_block_verification_and_import_time_count            |                                                              |           |        |
| polkadot_build_info                                          | A metric with a constant '1' value labeled by name, version  | gauge     |        |
| polkadot_database_cache_bytes                                | RocksDB cache size in bytes                                  | gauge     |        |
| polkadot_finality_grandpa_precommits_total                   | Total number of GRANDPA precommits cast locally.             | counter   |        |
| polkadot_finality_grandpa_prevotes_total                     | Total number of GRANDPA prevotes cast locally.               | counter   |        |
| polkadot_finality_grandpa_round                              | Highest completed GRANDPA round.                             | gauge     |        |
| polkadot_finality_grandpa_until_imported_waiting_messages_number | Number of finality grandpa messages waiting within the until imported queue. | gauge     |        |
| polkadot_import_queue_blocks_submitted                       | Number of blocks submitted to the import queue.              | counter   |        |
| polkadot_import_queue_justifications_submitted               | Number of justifications submitted to the import queue.      | counter   |        |
| polkadot_issued_light_requests                               | Number of light client requests that our node has issued.    | counter   |        |
| polkadot_justification_import_time_bucket                    | Time taken to import justifications                          | histogram |        |
| polkadot_justification_import_time_sum                       |                                                              |           |        |
| polkadot_justification_import_time_count                     |                                                              |           |        |
| polkadot_network_gossip_expired_messages_total               | Number of expired messages by the gossip service.            | counter   |        |
| polkadot_network_gossip_registered_messages_total            | Number of registered messages by the gossip service.         | counter   |        |
| polkadot_node_roles                                          | The roles the node is running as                             | gauge     |        |
| polkadot_number_leaves                                       | Number of known chain leaves (aka forks)                     | gauge     |        |
| polkadot_parachain_activated_heads_total                     | Number of activated heads.                                   | counter   |        |
| polkadot_parachain_approval_checking_finality_lag            | How far behind the head of the chain the Approval Checking protocol wants to vote | gauge     |        |
| polkadot_parachain_approvals_blockapproval_time_ticks_bucket | Number of ticks (500ms) to approve blocks.                   | histogram |        |
| polkadot_parachain_approvals_blockapproval_time_ticks_sum    |                                                              |           |        |
| polkadot_parachain_approvals_blockapproval_time_ticks_count  |                                                              |           |        |
| polkadot_parachain_approvals_candidate_approval_time_ticks_bucket | Number of ticks (500ms) to approve candidates.               | histogram |        |
| polkadot_parachain_approvals_candidate_approval_time_ticks_sum |                                                              |           |        |
| polkadot_parachain_approvals_candidate_approval_time_ticks_count |                                                              |           |        |
| polkadot_parachain_approvals_imported_total                  | Number of valid approvals imported locally or from other peers. | counter   |        |
| polkadot_parachain_approvals_no_shows_total                  | Number of assignments which became no-shows in the approval voting subsystem | counter   |        |
| polkadot_parachain_approvals_wakeups_total                   | Number of times we woke up to process a candidate in the approval voting subsystem | counter   |        |
| polkadot_parachain_assignments_imported_total                | Number of valid assignments imported locally or from other peers. | counter   |        |
| polkadot_parachain_assignments_produced_bucket               | Assignments and tranches produced by the approval voting subsystem | histogram |        |
| polkadot_parachain_assignments_produced_sum                  |                                                              |           |        |
| polkadot_parachain_assignments_produced_count                |                                                              |           |        |
| polkadot_parachain_av_store_block_activated_bucket           | Time spent within `av_store::process_block_activated`        | histogram |        |
| polkadot_parachain_av_store_block_activated_sum              |                                                              |           |        |
| polkadot_parachain_av_store_block_activated_count            |                                                              |           |        |
| polkadot_parachain_av_store_get_chunk_bucket                 | Time spent fetching requested chunks.                        | histogram |        |
| polkadot_parachain_av_store_get_chunk_sum                    |                                                              |           |        |
| polkadot_parachain_av_store_get_chunk_count                  |                                                              |           |        |
| polkadot_parachain_av_store_process_block_finalized_bucket   | Time spent within `av_store::process_block_finalized`        | histogram |        |
| polkadot_parachain_av_store_process_block_finalized_sum      |                                                              |           |        |
| polkadot_parachain_av_store_process_block_finalized_count    |                                                              |           |        |
| polkadot_parachain_av_store_process_message_bucket           | Time spent within `av_store::process_message`                | histogram |        |
| polkadot_parachain_av_store_process_message_sum              |                                                              |           |        |
| polkadot_parachain_av_store_process_message_count            |                                                              |           |        |
| polkadot_parachain_av_store_pruning_bucket                   | Time spent within `av_store::prune_all`                      | histogram |        |
| polkadot_parachain_av_store_pruning_sum                      |                                                              |           |        |
| polkadot_parachain_av_store_pruning_count                    |                                                              |           |        |
| polkadot_parachain_av_store_store_available_data_bucket      | Time spent within `av_store::store_available_data`           | histogram |        |
| polkadot_parachain_av_store_store_available_data_sum         |                                                              |           |        |
| polkadot_parachain_av_store_store_available_data_count       |                                                              |           |        |
| polkadot_parachain_av_store_store_chunk_bucket               | Time spent within `av_store::store_chunk`                    | histogram |        |
| polkadot_parachain_av_store_store_chunk_sum                  |                                                              |           |        |
| polkadot_parachain_av_store_store_chunk_count                |                                                              |           |        |
| polkadot_parachain_bitfield_distribution_active_leaves_update_bucket | Time spent within `bitfield_distribution::active_leaves_update` | histogram |        |
| polkadot_parachain_bitfield_distribution_active_leaves_update_sum |                                                              |           |        |
| polkadot_parachain_bitfield_distribution_active_leaves_update_count |                                                              |           |        |
| polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket | Time spent within `bitfield_distribution::handle_bitfield_distribution` | histogram |        |
| polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_sum |                                                              |           |        |
| polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_count |                                                              |           |        |
| polkadot_parachain_bitfield_distribution_handle_network_msg_bucket | Time spent within `bitfield_distribution::handle_network_msg` | histogram |        |
| polkadot_parachain_bitfield_distribution_handle_network_msg_sum |                                                              |           |        |
| polkadot_parachain_bitfield_distribution_handle_network_msg_count |                                                              |           |        |
| polkadot_parachain_bitfield_signing_run_bucket               | Time spent within `bitfield_signing::run`                    | histogram |        |
| polkadot_parachain_bitfield_signing_run_sum                  |                                                              |           |        |
| polkadot_parachain_bitfield_signing_run_count                |                                                              |           |        |
| polkadot_parachain_bitfields_signed_total                    | Number of bitfields signed.                                  | counter   |        |
| polkadot_parachain_candidate_backing_candidates_seconded_total | Number of candidates seconded.                               | counter   |        |
| polkadot_parachain_candidate_backing_get_backed_candidates_bucket | Time spent within `candidate_backing::get_backed_candidates` | histogram |        |
| polkadot_parachain_candidate_backing_get_backed_candidates_sum |                                                              |           |        |
| polkadot_parachain_candidate_backing_get_backed_candidates_count |                                                              |           |        |
| polkadot_parachain_candidate_backing_process_second_bucket   | Time spent within `candidate_backing::process_second`        | histogram |        |
| polkadot_parachain_candidate_backing_process_second_sum      |                                                              |           |        |
| polkadot_parachain_candidate_backing_process_second_count    |                                                              |           |        |
| polkadot_parachain_candidate_backing_process_statement_bucket | Time spent within `candidate_backing::process_statement`     | histogram |        |
| polkadot_parachain_candidate_backing_process_statement_sum   |                                                              |           |        |
| polkadot_parachain_candidate_backing_process_statement_count |                                                              |           |        |
| polkadot_parachain_candidate_backing_signed_statements_total | Number of statements signed.                                 | counter   |        |
| polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket | Time spent within `candidate_validation::validate_candidate_exhaustive` | histogram |        |
| polkadot_parachain_candidate_validation_validate_candidate_exhaustive_sum |                                                              |           |        |
| polkadot_parachain_candidate_validation_validate_candidate_exhaustive_count |                                                              |           |        |
| polkadot_parachain_candidate_validation_validate_from_chain_state_bucket | Time spent within `candidate_validation::validate_from_chain_state` | histogram |        |
| polkadot_parachain_candidate_validation_validate_from_chain_state_sum |                                                              |           |        |
| polkadot_parachain_candidate_validation_validate_from_chain_state_count |                                                              |           |        |
| polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket | Time spent within `candidate_validation::validate_from_exhaustive` | histogram |        |
| polkadot_parachain_candidate_validation_validate_from_exhaustive_sum |                                                              |           |        |
| polkadot_parachain_candidate_validation_validate_from_exhaustive_count |                                                              |           |        |
| polkadot_parachain_chain_api_ancestors_bucket                | Time spent within `chain_api::ancestors`                     | histogram |        |
| polkadot_parachain_chain_api_ancestors_sum                   |                                                              |           |        |
| polkadot_parachain_chain_api_ancestors_count                 |                                                              |           |        |
| polkadot_parachain_chain_api_block_headers_bucket            | Time spent within `chain_api::block_headers`                 | histogram |        |
| polkadot_parachain_chain_api_block_headers_sum               |                                                              |           |        |
| polkadot_parachain_chain_api_block_headers_count             |                                                              |           |        |
| polkadot_parachain_chain_api_block_number_bucket             | Time spent within `chain_api::block_number`                  | histogram |        |
| polkadot_parachain_chain_api_block_number_sum                |                                                              |           |        |
| polkadot_parachain_chain_api_block_number_count              |                                                              |           |        |
| polkadot_parachain_chain_api_block_weight_bucket             | Time spent within `chain_api::block_weight`                  | histogram |        |
| polkadot_parachain_chain_api_block_weight_sum                |                                                              |           |        |
| polkadot_parachain_chain_api_block_weight_count              |                                                              |           |        |
| polkadot_parachain_chain_api_finalized_block_hash_bucket     | Time spent within `chain_api::finalized_block_hash`          | histogram |        |
| polkadot_parachain_chain_api_finalized_block_hash_sum        |                                                              |           |        |
| polkadot_parachain_chain_api_finalized_block_hash_count      |                                                              |           |        |
| polkadot_parachain_chain_api_finalized_block_number_bucket   | Time spent within `chain_api::finalized_block_number`        | histogram |        |
| polkadot_parachain_chain_api_finalized_block_number_sum      |                                                              |           |        |
| polkadot_parachain_chain_api_finalized_block_number_count    |                                                              |           |        |
| polkadot_parachain_chain_api_requests_total                  | Number of Chain API requests served.                         | counter   |        |
| polkadot_parachain_collation_advertisements_made_total       | A number of collation advertisements sent to validators.     | counter   |        |
| polkadot_parachain_collation_generation_new_activations_bucket | Time spent within fn handle_new_activations                  | histogram |        |
| polkadot_parachain_collation_generation_new_activations_sum  |                                                              |           |        |
| polkadot_parachain_collation_generation_new_activations_count |                                                              |           |        |
| polkadot_parachain_collation_generation_per_availability_core_bucket | Time spent handling a particular availability core for a relay parent in fn `handle_new_activations` | histogram |        |
| polkadot_parachain_collation_generation_per_availability_core_sum |                                                              |           |        |
| polkadot_parachain_collation_generation_per_availability_core_count |                                                              |           |        |
|                                                              |                                                              |           |        |
|                                                              |                                                              |           |        |
|                                                              |                                                              |           |        |
|                                                              |                                                              |           |        |
|                                                              |                                                              |           |        |
|                                                              |                                                              |           |        |





