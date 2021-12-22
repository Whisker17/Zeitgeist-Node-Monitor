# Metrics



```
# HELP polkadot_authority_discovery_amount_external_addresses_last_published Number of external addresses published when authority discovery last published addresses.
# TYPE polkadot_authority_discovery_amount_external_addresses_last_published gauge
polkadot_authority_discovery_amount_external_addresses_last_published 0
# HELP polkadot_authority_discovery_authority_address_requests_pending Number of pending authority address requests.
# TYPE polkadot_authority_discovery_authority_address_requests_pending gauge
polkadot_authority_discovery_authority_address_requests_pending 0
# HELP polkadot_authority_discovery_authority_addresses_requested_total Number of times authority discovery has requested external addresses of a single authority.
# TYPE polkadot_authority_discovery_authority_addresses_requested_total counter
polkadot_authority_discovery_authority_addresses_requested_total 36
# HELP polkadot_authority_discovery_dht_event_received Number of dht events received by authority discovery.
# TYPE polkadot_authority_discovery_dht_event_received counter
polkadot_authority_discovery_dht_event_received{name="value_not_found"} 36
# HELP polkadot_authority_discovery_handle_value_found_event_failure Number of times handling a dht value found event failed.
# TYPE polkadot_authority_discovery_handle_value_found_event_failure counter
polkadot_authority_discovery_handle_value_found_event_failure 0
# HELP polkadot_authority_discovery_known_authorities_count Number of authorities known by authority discovery.
# TYPE polkadot_authority_discovery_known_authorities_count gauge
polkadot_authority_discovery_known_authorities_count 0
# HELP polkadot_authority_discovery_times_published_total Number of times authority discovery has published external addresses.
# TYPE polkadot_authority_discovery_times_published_total counter
polkadot_authority_discovery_times_published_total 0
# HELP polkadot_block_height Block height info of the chain
# TYPE polkadot_block_height gauge
polkadot_block_height{status="best"} 267509
polkadot_block_height{status="finalized"} 267501
# HELP polkadot_block_verification_and_import_time Time taken to verify and import blocks
# TYPE polkadot_block_verification_and_import_time histogram
polkadot_block_verification_and_import_time_bucket{le="0.005"} 0
polkadot_block_verification_and_import_time_bucket{le="0.01"} 0
polkadot_block_verification_and_import_time_bucket{le="0.025"} 0
polkadot_block_verification_and_import_time_bucket{le="0.05"} 0
polkadot_block_verification_and_import_time_bucket{le="0.1"} 0
polkadot_block_verification_and_import_time_bucket{le="0.25"} 0
polkadot_block_verification_and_import_time_bucket{le="0.5"} 0
polkadot_block_verification_and_import_time_bucket{le="1"} 0
polkadot_block_verification_and_import_time_bucket{le="2.5"} 0
polkadot_block_verification_and_import_time_bucket{le="5"} 0
polkadot_block_verification_and_import_time_bucket{le="10"} 0
polkadot_block_verification_and_import_time_bucket{le="+Inf"} 0
polkadot_block_verification_and_import_time_sum 0
polkadot_block_verification_and_import_time_count 0
# HELP polkadot_build_info A metric with a constant '1' value labeled by name, version
# TYPE polkadot_build_info gauge
polkadot_build_info{name="torpid-cheese-1287",version="0.2.1-a9ff969-x86_64-linux-gnu"} 1
# HELP polkadot_database_cache_bytes RocksDB cache size in bytes
# TYPE polkadot_database_cache_bytes gauge
polkadot_database_cache_bytes 0
# HELP polkadot_finality_grandpa_precommits_total Total number of GRANDPA precommits cast locally.
# TYPE polkadot_finality_grandpa_precommits_total counter
polkadot_finality_grandpa_precommits_total 0
# HELP polkadot_finality_grandpa_prevotes_total Total number of GRANDPA prevotes cast locally.
# TYPE polkadot_finality_grandpa_prevotes_total counter
polkadot_finality_grandpa_prevotes_total 0
# HELP polkadot_finality_grandpa_round Highest completed GRANDPA round.
# TYPE polkadot_finality_grandpa_round gauge
polkadot_finality_grandpa_round 0
# HELP polkadot_finality_grandpa_until_imported_waiting_messages_number Number of finality grandpa messages waiting within the until imported queue.
# TYPE polkadot_finality_grandpa_until_imported_waiting_messages_number gauge
polkadot_finality_grandpa_until_imported_waiting_messages_number 0
# HELP polkadot_import_queue_blocks_submitted Number of blocks submitted to the import queue.
# TYPE polkadot_import_queue_blocks_submitted counter
polkadot_import_queue_blocks_submitted 0
# HELP polkadot_import_queue_justifications_submitted Number of justifications submitted to the import queue.
# TYPE polkadot_import_queue_justifications_submitted counter
polkadot_import_queue_justifications_submitted 0
# HELP polkadot_issued_light_requests Number of light client requests that our node has issued.
# TYPE polkadot_issued_light_requests counter
polkadot_issued_light_requests 0
# HELP polkadot_justification_import_time Time taken to import justifications
# TYPE polkadot_justification_import_time histogram
polkadot_justification_import_time_bucket{le="0.005"} 0
polkadot_justification_import_time_bucket{le="0.01"} 0
polkadot_justification_import_time_bucket{le="0.025"} 0
polkadot_justification_import_time_bucket{le="0.05"} 0
polkadot_justification_import_time_bucket{le="0.1"} 0
polkadot_justification_import_time_bucket{le="0.25"} 0
polkadot_justification_import_time_bucket{le="0.5"} 0
polkadot_justification_import_time_bucket{le="1"} 0
polkadot_justification_import_time_bucket{le="2.5"} 0
polkadot_justification_import_time_bucket{le="5"} 0
polkadot_justification_import_time_bucket{le="10"} 0
polkadot_justification_import_time_bucket{le="+Inf"} 0
polkadot_justification_import_time_sum 0
polkadot_justification_import_time_count 0
# HELP polkadot_network_gossip_expired_messages_total Number of expired messages by the gossip service.
# TYPE polkadot_network_gossip_expired_messages_total counter
polkadot_network_gossip_expired_messages_total 0
# HELP polkadot_network_gossip_registered_messages_total Number of registered messages by the gossip service.
# TYPE polkadot_network_gossip_registered_messages_total counter
polkadot_network_gossip_registered_messages_total 0
# HELP polkadot_node_roles The roles the node is running as
# TYPE polkadot_node_roles gauge
polkadot_node_roles 1
# HELP polkadot_number_leaves Number of known chain leaves (aka forks)
# TYPE polkadot_number_leaves gauge
polkadot_number_leaves 1
# HELP polkadot_parachain_activated_heads_total Number of activated heads.
# TYPE polkadot_parachain_activated_heads_total counter
polkadot_parachain_activated_heads_total 1
# HELP polkadot_parachain_approval_checking_finality_lag How far behind the head of the chain the Approval Checking protocol wants to vote
# TYPE polkadot_parachain_approval_checking_finality_lag gauge
polkadot_parachain_approval_checking_finality_lag 0
# HELP polkadot_parachain_approvals_blockapproval_time_ticks Number of ticks (500ms) to approve blocks.
# TYPE polkadot_parachain_approvals_blockapproval_time_ticks histogram
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="6"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="12"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="18"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="24"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="30"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="36"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="72"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="100"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="144"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_bucket{le="+Inf"} 0
polkadot_parachain_approvals_blockapproval_time_ticks_sum 0
polkadot_parachain_approvals_blockapproval_time_ticks_count 0
# HELP polkadot_parachain_approvals_candidate_approval_time_ticks Number of ticks (500ms) to approve candidates.
# TYPE polkadot_parachain_approvals_candidate_approval_time_ticks histogram
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="6"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="12"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="18"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="24"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="30"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="36"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="72"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="100"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="144"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_bucket{le="+Inf"} 0
polkadot_parachain_approvals_candidate_approval_time_ticks_sum 0
polkadot_parachain_approvals_candidate_approval_time_ticks_count 0
# HELP polkadot_parachain_approvals_imported_total Number of valid approvals imported locally or from other peers.
# TYPE polkadot_parachain_approvals_imported_total counter
polkadot_parachain_approvals_imported_total 0
# HELP polkadot_parachain_approvals_no_shows_total Number of assignments which became no-shows in the approval voting subsystem
# TYPE polkadot_parachain_approvals_no_shows_total counter
polkadot_parachain_approvals_no_shows_total 0
# HELP polkadot_parachain_approvals_wakeups_total Number of times we woke up to process a candidate in the approval voting subsystem
# TYPE polkadot_parachain_approvals_wakeups_total counter
polkadot_parachain_approvals_wakeups_total 0
# HELP polkadot_parachain_assignments_imported_total Number of valid assignments imported locally or from other peers.
# TYPE polkadot_parachain_assignments_imported_total counter
polkadot_parachain_assignments_imported_total 0
# HELP polkadot_parachain_assignments_produced Assignments and tranches produced by the approval voting subsystem
# TYPE polkadot_parachain_assignments_produced histogram
polkadot_parachain_assignments_produced_bucket{le="0"} 0
polkadot_parachain_assignments_produced_bucket{le="1"} 0
polkadot_parachain_assignments_produced_bucket{le="2"} 0
polkadot_parachain_assignments_produced_bucket{le="3"} 0
polkadot_parachain_assignments_produced_bucket{le="4"} 0
polkadot_parachain_assignments_produced_bucket{le="5"} 0
polkadot_parachain_assignments_produced_bucket{le="10"} 0
polkadot_parachain_assignments_produced_bucket{le="15"} 0
polkadot_parachain_assignments_produced_bucket{le="25"} 0
polkadot_parachain_assignments_produced_bucket{le="40"} 0
polkadot_parachain_assignments_produced_bucket{le="70"} 0
polkadot_parachain_assignments_produced_bucket{le="+Inf"} 0
polkadot_parachain_assignments_produced_sum 0
polkadot_parachain_assignments_produced_count 0
# HELP polkadot_parachain_av_store_block_activated Time spent within `av_store::process_block_activated`
# TYPE polkadot_parachain_av_store_block_activated histogram
polkadot_parachain_av_store_block_activated_bucket{le="0.005"} 0
polkadot_parachain_av_store_block_activated_bucket{le="0.01"} 0
polkadot_parachain_av_store_block_activated_bucket{le="0.025"} 0
polkadot_parachain_av_store_block_activated_bucket{le="0.05"} 0
polkadot_parachain_av_store_block_activated_bucket{le="0.1"} 1
polkadot_parachain_av_store_block_activated_bucket{le="0.25"} 1
polkadot_parachain_av_store_block_activated_bucket{le="0.5"} 1
polkadot_parachain_av_store_block_activated_bucket{le="1"} 1
polkadot_parachain_av_store_block_activated_bucket{le="2.5"} 1
polkadot_parachain_av_store_block_activated_bucket{le="5"} 1
polkadot_parachain_av_store_block_activated_bucket{le="10"} 1
polkadot_parachain_av_store_block_activated_bucket{le="+Inf"} 1
polkadot_parachain_av_store_block_activated_sum 0.068864346
polkadot_parachain_av_store_block_activated_count 1
# HELP polkadot_parachain_av_store_get_chunk Time spent fetching requested chunks.`
# TYPE polkadot_parachain_av_store_get_chunk histogram
polkadot_parachain_av_store_get_chunk_bucket{le="0.005"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="0.01"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="0.025"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="0.05"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="0.1"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="0.25"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="0.5"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="1"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="2.5"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="5"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="10"} 0
polkadot_parachain_av_store_get_chunk_bucket{le="+Inf"} 0
polkadot_parachain_av_store_get_chunk_sum 0
polkadot_parachain_av_store_get_chunk_count 0
# HELP polkadot_parachain_av_store_process_block_finalized Time spent within `av_store::process_block_finalized`
# TYPE polkadot_parachain_av_store_process_block_finalized histogram
polkadot_parachain_av_store_process_block_finalized_bucket{le="0.005"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="0.01"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="0.025"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="0.05"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="0.1"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="0.25"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="0.5"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="1"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="2.5"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="5"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="10"} 0
polkadot_parachain_av_store_process_block_finalized_bucket{le="+Inf"} 0
polkadot_parachain_av_store_process_block_finalized_sum 0
polkadot_parachain_av_store_process_block_finalized_count 0
# HELP polkadot_parachain_av_store_process_message Time spent within `av_store::process_message`
# TYPE polkadot_parachain_av_store_process_message histogram
polkadot_parachain_av_store_process_message_bucket{le="0.005"} 0
polkadot_parachain_av_store_process_message_bucket{le="0.01"} 0
polkadot_parachain_av_store_process_message_bucket{le="0.025"} 0
polkadot_parachain_av_store_process_message_bucket{le="0.05"} 0
polkadot_parachain_av_store_process_message_bucket{le="0.1"} 0
polkadot_parachain_av_store_process_message_bucket{le="0.25"} 0
polkadot_parachain_av_store_process_message_bucket{le="0.5"} 0
polkadot_parachain_av_store_process_message_bucket{le="1"} 0
polkadot_parachain_av_store_process_message_bucket{le="2.5"} 0
polkadot_parachain_av_store_process_message_bucket{le="5"} 0
polkadot_parachain_av_store_process_message_bucket{le="10"} 0
polkadot_parachain_av_store_process_message_bucket{le="+Inf"} 0
polkadot_parachain_av_store_process_message_sum 0
polkadot_parachain_av_store_process_message_count 0
# HELP polkadot_parachain_av_store_pruning Time spent within `av_store::prune_all`
# TYPE polkadot_parachain_av_store_pruning histogram
polkadot_parachain_av_store_pruning_bucket{le="0.005"} 22
polkadot_parachain_av_store_pruning_bucket{le="0.01"} 22
polkadot_parachain_av_store_pruning_bucket{le="0.025"} 22
polkadot_parachain_av_store_pruning_bucket{le="0.05"} 22
polkadot_parachain_av_store_pruning_bucket{le="0.1"} 22
polkadot_parachain_av_store_pruning_bucket{le="0.25"} 22
polkadot_parachain_av_store_pruning_bucket{le="0.5"} 22
polkadot_parachain_av_store_pruning_bucket{le="1"} 22
polkadot_parachain_av_store_pruning_bucket{le="2.5"} 22
polkadot_parachain_av_store_pruning_bucket{le="5"} 22
polkadot_parachain_av_store_pruning_bucket{le="10"} 22
polkadot_parachain_av_store_pruning_bucket{le="+Inf"} 22
polkadot_parachain_av_store_pruning_sum 0.0013225459999999997
polkadot_parachain_av_store_pruning_count 22
# HELP polkadot_parachain_av_store_store_available_data Time spent within `av_store::store_available_data`
# TYPE polkadot_parachain_av_store_store_available_data histogram
polkadot_parachain_av_store_store_available_data_bucket{le="0.005"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="0.01"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="0.025"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="0.05"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="0.1"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="0.25"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="0.5"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="1"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="2.5"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="5"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="10"} 0
polkadot_parachain_av_store_store_available_data_bucket{le="+Inf"} 0
polkadot_parachain_av_store_store_available_data_sum 0
polkadot_parachain_av_store_store_available_data_count 0
# HELP polkadot_parachain_av_store_store_chunk Time spent within `av_store::store_chunk`
# TYPE polkadot_parachain_av_store_store_chunk histogram
polkadot_parachain_av_store_store_chunk_bucket{le="0.005"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="0.01"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="0.025"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="0.05"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="0.1"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="0.25"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="0.5"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="1"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="2.5"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="5"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="10"} 0
polkadot_parachain_av_store_store_chunk_bucket{le="+Inf"} 0
polkadot_parachain_av_store_store_chunk_sum 0
polkadot_parachain_av_store_store_chunk_count 0
# HELP polkadot_parachain_bitfield_distribution_active_leaves_update Time spent within `bitfield_distribution::active_leaves_update`
# TYPE polkadot_parachain_bitfield_distribution_active_leaves_update histogram
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="0.005"} 0
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="0.01"} 0
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="0.025"} 0
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="0.05"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="0.1"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="0.25"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="0.5"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="1"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="2.5"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="5"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="10"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_bucket{le="+Inf"} 1
polkadot_parachain_bitfield_distribution_active_leaves_update_sum 0.029822573
polkadot_parachain_bitfield_distribution_active_leaves_update_count 1
# HELP polkadot_parachain_bitfield_distribution_handle_bitfield_distribution Time spent within `bitfield_distribution::handle_bitfield_distribution`
# TYPE polkadot_parachain_bitfield_distribution_handle_bitfield_distribution histogram
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="0.005"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="0.01"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="0.025"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="0.05"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="0.1"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="0.25"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="0.5"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="1"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="2.5"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="5"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="10"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket{le="+Inf"} 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_sum 0
polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_count 0
# HELP polkadot_parachain_bitfield_distribution_handle_network_msg Time spent within `bitfield_distribution::handle_network_msg`
# TYPE polkadot_parachain_bitfield_distribution_handle_network_msg histogram
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="0.005"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="0.01"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="0.025"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="0.05"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="0.1"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="0.25"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="0.5"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="1"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="2.5"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="5"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="10"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_bucket{le="+Inf"} 1
polkadot_parachain_bitfield_distribution_handle_network_msg_sum 0.000012234
polkadot_parachain_bitfield_distribution_handle_network_msg_count 1
# HELP polkadot_parachain_bitfield_signing_run Time spent within `bitfield_signing::run`
# TYPE polkadot_parachain_bitfield_signing_run histogram
polkadot_parachain_bitfield_signing_run_bucket{le="0.005"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="0.01"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="0.025"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="0.05"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="0.1"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="0.25"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="0.5"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="1"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="2.5"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="5"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="10"} 0
polkadot_parachain_bitfield_signing_run_bucket{le="+Inf"} 0
polkadot_parachain_bitfield_signing_run_sum 0
polkadot_parachain_bitfield_signing_run_count 0
# HELP polkadot_parachain_bitfields_signed_total Number of bitfields signed.
# TYPE polkadot_parachain_bitfields_signed_total counter
polkadot_parachain_bitfields_signed_total 0
# HELP polkadot_parachain_candidate_backing_candidates_seconded_total Number of candidates seconded.
# TYPE polkadot_parachain_candidate_backing_candidates_seconded_total counter
polkadot_parachain_candidate_backing_candidates_seconded_total 0
# HELP polkadot_parachain_candidate_backing_get_backed_candidates Time spent within `candidate_backing::get_backed_candidates`
# TYPE polkadot_parachain_candidate_backing_get_backed_candidates histogram
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="0.005"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="0.01"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="0.025"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="0.05"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="0.1"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="0.25"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="0.5"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="1"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="2.5"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="5"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="10"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_bucket{le="+Inf"} 0
polkadot_parachain_candidate_backing_get_backed_candidates_sum 0
polkadot_parachain_candidate_backing_get_backed_candidates_count 0
# HELP polkadot_parachain_candidate_backing_process_second Time spent within `candidate_backing::process_second`
# TYPE polkadot_parachain_candidate_backing_process_second histogram
polkadot_parachain_candidate_backing_process_second_bucket{le="0.005"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="0.01"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="0.025"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="0.05"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="0.1"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="0.25"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="0.5"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="1"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="2.5"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="5"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="10"} 0
polkadot_parachain_candidate_backing_process_second_bucket{le="+Inf"} 0
polkadot_parachain_candidate_backing_process_second_sum 0
polkadot_parachain_candidate_backing_process_second_count 0
# HELP polkadot_parachain_candidate_backing_process_statement Time spent within `candidate_backing::process_statement`
# TYPE polkadot_parachain_candidate_backing_process_statement histogram
polkadot_parachain_candidate_backing_process_statement_bucket{le="0.005"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="0.01"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="0.025"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="0.05"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="0.1"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="0.25"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="0.5"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="1"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="2.5"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="5"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="10"} 0
polkadot_parachain_candidate_backing_process_statement_bucket{le="+Inf"} 0
polkadot_parachain_candidate_backing_process_statement_sum 0
polkadot_parachain_candidate_backing_process_statement_count 0
# HELP polkadot_parachain_candidate_backing_signed_statements_total Number of statements signed.
# TYPE polkadot_parachain_candidate_backing_signed_statements_total counter
polkadot_parachain_candidate_backing_signed_statements_total 0
# HELP polkadot_parachain_candidate_validation_validate_candidate_exhaustive Time spent within `candidate_validation::validate_candidate_exhaustive`
# TYPE polkadot_parachain_candidate_validation_validate_candidate_exhaustive histogram
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="0.005"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="0.01"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="0.025"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="0.05"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="0.1"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="0.25"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="0.5"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="1"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="2.5"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="5"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="10"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket{le="+Inf"} 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_sum 0
polkadot_parachain_candidate_validation_validate_candidate_exhaustive_count 0
# HELP polkadot_parachain_candidate_validation_validate_from_chain_state Time spent within `candidate_validation::validate_from_chain_state`
# TYPE polkadot_parachain_candidate_validation_validate_from_chain_state histogram
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="0.005"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="0.01"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="0.025"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="0.05"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="0.1"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="0.25"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="0.5"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="1"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="2.5"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="5"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="10"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_bucket{le="+Inf"} 0
polkadot_parachain_candidate_validation_validate_from_chain_state_sum 0
polkadot_parachain_candidate_validation_validate_from_chain_state_count 0
# HELP polkadot_parachain_candidate_validation_validate_from_exhaustive Time spent within `candidate_validation::validate_from_exhaustive`
# TYPE polkadot_parachain_candidate_validation_validate_from_exhaustive histogram
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="0.005"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="0.01"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="0.025"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="0.05"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="0.1"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="0.25"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="0.5"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="1"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="2.5"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="5"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="10"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket{le="+Inf"} 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_sum 0
polkadot_parachain_candidate_validation_validate_from_exhaustive_count 0
# HELP polkadot_parachain_chain_api_ancestors Time spent within `chain_api::ancestors`
# TYPE polkadot_parachain_chain_api_ancestors histogram
polkadot_parachain_chain_api_ancestors_bucket{le="0.005"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="0.01"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="0.025"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="0.05"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="0.1"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="0.25"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="0.5"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="1"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="2.5"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="5"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="10"} 0
polkadot_parachain_chain_api_ancestors_bucket{le="+Inf"} 0
polkadot_parachain_chain_api_ancestors_sum 0
polkadot_parachain_chain_api_ancestors_count 0
# HELP polkadot_parachain_chain_api_block_headers Time spent within `chain_api::block_headers`
# TYPE polkadot_parachain_chain_api_block_headers histogram
polkadot_parachain_chain_api_block_headers_bucket{le="0.005"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="0.01"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="0.025"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="0.05"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="0.1"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="0.25"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="0.5"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="1"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="2.5"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="5"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="10"} 3
polkadot_parachain_chain_api_block_headers_bucket{le="+Inf"} 3
polkadot_parachain_chain_api_block_headers_sum 0.000045916
polkadot_parachain_chain_api_block_headers_count 3
# HELP polkadot_parachain_chain_api_block_number Time spent within `chain_api::block_number`
# TYPE polkadot_parachain_chain_api_block_number histogram
polkadot_parachain_chain_api_block_number_bucket{le="0.005"} 0
polkadot_parachain_chain_api_block_number_bucket{le="0.01"} 0
polkadot_parachain_chain_api_block_number_bucket{le="0.025"} 0
polkadot_parachain_chain_api_block_number_bucket{le="0.05"} 0
polkadot_parachain_chain_api_block_number_bucket{le="0.1"} 0
polkadot_parachain_chain_api_block_number_bucket{le="0.25"} 0
polkadot_parachain_chain_api_block_number_bucket{le="0.5"} 0
polkadot_parachain_chain_api_block_number_bucket{le="1"} 0
polkadot_parachain_chain_api_block_number_bucket{le="2.5"} 0
polkadot_parachain_chain_api_block_number_bucket{le="5"} 0
polkadot_parachain_chain_api_block_number_bucket{le="10"} 0
polkadot_parachain_chain_api_block_number_bucket{le="+Inf"} 0
polkadot_parachain_chain_api_block_number_sum 0
polkadot_parachain_chain_api_block_number_count 0
# HELP polkadot_parachain_chain_api_block_weight Time spent within `chain_api::block_weight`
# TYPE polkadot_parachain_chain_api_block_weight histogram
polkadot_parachain_chain_api_block_weight_bucket{le="0.005"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="0.01"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="0.025"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="0.05"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="0.1"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="0.25"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="0.5"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="1"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="2.5"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="5"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="10"} 0
polkadot_parachain_chain_api_block_weight_bucket{le="+Inf"} 0
polkadot_parachain_chain_api_block_weight_sum 0
polkadot_parachain_chain_api_block_weight_count 0
# HELP polkadot_parachain_chain_api_finalized_block_hash Time spent within `chain_api::finalized_block_hash`
# TYPE polkadot_parachain_chain_api_finalized_block_hash histogram
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="0.005"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="0.01"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="0.025"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="0.05"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="0.1"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="0.25"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="0.5"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="1"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="2.5"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="5"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="10"} 0
polkadot_parachain_chain_api_finalized_block_hash_bucket{le="+Inf"} 0
polkadot_parachain_chain_api_finalized_block_hash_sum 0
polkadot_parachain_chain_api_finalized_block_hash_count 0
# HELP polkadot_parachain_chain_api_finalized_block_number Time spent within `chain_api::finalized_block_number`
# TYPE polkadot_parachain_chain_api_finalized_block_number histogram
polkadot_parachain_chain_api_finalized_block_number_bucket{le="0.005"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="0.01"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="0.025"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="0.05"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="0.1"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="0.25"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="0.5"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="1"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="2.5"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="5"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="10"} 0
polkadot_parachain_chain_api_finalized_block_number_bucket{le="+Inf"} 0
polkadot_parachain_chain_api_finalized_block_number_sum 0
polkadot_parachain_chain_api_finalized_block_number_count 0
# HELP polkadot_parachain_chain_api_requests_total Number of Chain API requests served.
# TYPE polkadot_parachain_chain_api_requests_total counter
polkadot_parachain_chain_api_requests_total{success="succeeded"} 3
# HELP polkadot_parachain_collation_advertisements_made_total A number of collation advertisements sent to validators.
# TYPE polkadot_parachain_collation_advertisements_made_total counter
polkadot_parachain_collation_advertisements_made_total 0
# HELP polkadot_parachain_collation_generation_new_activations Time spent within fn handle_new_activations
# TYPE polkadot_parachain_collation_generation_new_activations histogram
polkadot_parachain_collation_generation_new_activations_bucket{le="0.005"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="0.01"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="0.025"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="0.05"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="0.1"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="0.25"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="0.5"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="1"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="2.5"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="5"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="10"} 0
polkadot_parachain_collation_generation_new_activations_bucket{le="+Inf"} 0
polkadot_parachain_collation_generation_new_activations_sum 0
polkadot_parachain_collation_generation_new_activations_count 0
# HELP polkadot_parachain_collation_generation_per_availability_core Time spent handling a particular availability core for a relay parent in fn handle_new_activations
# TYPE polkadot_parachain_collation_generation_per_availability_core histogram
polkadot_parachain_collation_generation_per_availability_core_bucket{le="0.005"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="0.01"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="0.025"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="0.05"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="0.1"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="0.25"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="0.5"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="1"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="2.5"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="5"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="10"} 0
polkadot_parachain_collation_generation_per_availability_core_bucket{le="+Inf"} 0
polkadot_parachain_collation_generation_per_availability_core_sum 0
polkadot_parachain_collation_generation_per_availability_core_count 0
# HELP polkadot_parachain_collation_generation_per_relay_parent Time spent handling a particular relay parent within fn handle_new_activations
# TYPE polkadot_parachain_collation_generation_per_relay_parent histogram
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="0.005"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="0.01"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="0.025"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="0.05"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="0.1"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="0.25"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="0.5"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="1"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="2.5"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="5"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="10"} 0
polkadot_parachain_collation_generation_per_relay_parent_bucket{le="+Inf"} 0
polkadot_parachain_collation_generation_per_relay_parent_sum 0
polkadot_parachain_collation_generation_per_relay_parent_count 0
# HELP polkadot_parachain_collations_generated_total Number of collations generated.
# TYPE polkadot_parachain_collations_generated_total counter
polkadot_parachain_collations_generated_total 0
# HELP polkadot_parachain_collations_sent_requested_total A number of collations requested to be sent to validators.
# TYPE polkadot_parachain_collations_sent_requested_total counter
polkadot_parachain_collations_sent_requested_total 0
# HELP polkadot_parachain_collations_sent_total A number of collations sent to validators.
# TYPE polkadot_parachain_collations_sent_total counter
polkadot_parachain_collations_sent_total 0
# HELP polkadot_parachain_collator_protocol_collator_process_msg Time spent within `collator_protocol_collator::process_msg`
# TYPE polkadot_parachain_collator_protocol_collator_process_msg histogram
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="0.005"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="0.01"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="0.025"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="0.05"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="0.1"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="0.25"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="0.5"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="1"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="2.5"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="5"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="10"} 1
polkadot_parachain_collator_protocol_collator_process_msg_bucket{le="+Inf"} 1
polkadot_parachain_collator_protocol_collator_process_msg_sum 0.000004328
polkadot_parachain_collator_protocol_collator_process_msg_count 1
# HELP polkadot_parachain_deactivated_heads_total Number of deactivated heads.
# TYPE polkadot_parachain_deactivated_heads_total counter
polkadot_parachain_deactivated_heads_total 0
# HELP polkadot_parachain_dispute_distribution_received_requests Total number of received dispute requests.
# TYPE polkadot_parachain_dispute_distribution_received_requests counter
polkadot_parachain_dispute_distribution_received_requests 0
# HELP polkadot_parachain_disputes_finality_lag How far behind the head of the chain the Disputes protocol wants to vote
# TYPE polkadot_parachain_disputes_finality_lag gauge
polkadot_parachain_disputes_finality_lag 0
# HELP polkadot_parachain_fetch_retries_total Number of times we did not succeed in fetching a chunk and needed to try more backers.
# TYPE polkadot_parachain_fetch_retries_total counter
polkadot_parachain_fetch_retries_total 0
# HELP polkadot_parachain_gossipped_own_availabilty_bitfields_total Number of own availability bitfields sent to other peers.
# TYPE polkadot_parachain_gossipped_own_availabilty_bitfields_total counter
polkadot_parachain_gossipped_own_availabilty_bitfields_total 0
# HELP polkadot_parachain_imported_candidates_total Number of candidates imported by the approval voting subsystem
# TYPE polkadot_parachain_imported_candidates_total counter
polkadot_parachain_imported_candidates_total 0
# HELP polkadot_parachain_messages_relayed_total Number of messages relayed by Overseer.
# TYPE polkadot_parachain_messages_relayed_total counter
polkadot_parachain_messages_relayed_total 0
# HELP polkadot_parachain_notification_bytes_sent_total The number of bytes sent on a parachain notification protocol
# TYPE polkadot_parachain_notification_bytes_sent_total counter
polkadot_parachain_notification_bytes_sent_total{protocol="/polkadot/collation/1"} 0
polkadot_parachain_notification_bytes_sent_total{protocol="/polkadot/validation/1"} 0
# HELP polkadot_parachain_notifications_sent_total The number of notifications sent on a parachain protocol
# TYPE polkadot_parachain_notifications_sent_total counter
polkadot_parachain_notifications_sent_total{protocol="/polkadot/collation/1"} 0
polkadot_parachain_notifications_sent_total{protocol="/polkadot/validation/1"} 0
# HELP polkadot_parachain_overseer_signals_received Number of signals received by subsystems from overseer
# TYPE polkadot_parachain_overseer_signals_received gauge
polkadot_parachain_overseer_signals_received{subsystem_name="BitfieldSigning"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="CandidateBacking"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="Provisioning"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="approval-distribution-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="approval-voting-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="availability-distribution-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="availability-recovery-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="availability-store-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="bitfield-distribution-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="candidate-validation-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="chain-api-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="chain-selection-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="collation-generation-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="collator-protocol-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="dispute-coordinator-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="dispute-distribution-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="dispute-participation-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="gossip-support-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="network-bridge-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="runtime-api-subsystem"} 1
polkadot_parachain_overseer_signals_received{subsystem_name="statement-distribution-subsystem"} 1
# HELP polkadot_parachain_overseer_signals_sent Number of signals sent by overseer to subsystems
# TYPE polkadot_parachain_overseer_signals_sent gauge
polkadot_parachain_overseer_signals_sent{subsystem_name="BitfieldSigning"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="CandidateBacking"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="Provisioning"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="approval-distribution-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="approval-voting-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="availability-distribution-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="availability-recovery-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="availability-store-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="bitfield-distribution-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="candidate-validation-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="chain-api-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="chain-selection-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="collation-generation-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="collator-protocol-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="dispute-coordinator-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="dispute-distribution-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="dispute-participation-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="gossip-support-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="network-bridge-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="runtime-api-subsystem"} 1
polkadot_parachain_overseer_signals_sent{subsystem_name="statement-distribution-subsystem"} 1
# HELP polkadot_parachain_provisioner_provisionable_data Time spent within `provisioner::provisionable_data`
# TYPE polkadot_parachain_provisioner_provisionable_data histogram
polkadot_parachain_provisioner_provisionable_data_bucket{le="0.005"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="0.01"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="0.025"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="0.05"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="0.1"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="0.25"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="0.5"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="1"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="2.5"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="5"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="10"} 0
polkadot_parachain_provisioner_provisionable_data_bucket{le="+Inf"} 0
polkadot_parachain_provisioner_provisionable_data_sum 0
polkadot_parachain_provisioner_provisionable_data_count 0
# HELP polkadot_parachain_provisioner_request_inherent_data Time spent within `provisioner::request_inherent_data`
# TYPE polkadot_parachain_provisioner_request_inherent_data histogram
polkadot_parachain_provisioner_request_inherent_data_bucket{le="0.005"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="0.01"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="0.025"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="0.05"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="0.1"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="0.25"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="0.5"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="1"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="2.5"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="5"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="10"} 0
polkadot_parachain_provisioner_request_inherent_data_bucket{le="+Inf"} 0
polkadot_parachain_provisioner_request_inherent_data_sum 0
polkadot_parachain_provisioner_request_inherent_data_count 0
# HELP polkadot_parachain_received_availability_chunks_total Number of availability chunks received.
# TYPE polkadot_parachain_received_availability_chunks_total counter
polkadot_parachain_received_availability_chunks_total 0
# HELP polkadot_parachain_received_availabilty_bitfields_total Number of valid availability bitfields received from other peers.
# TYPE polkadot_parachain_received_availabilty_bitfields_total counter
polkadot_parachain_received_availabilty_bitfields_total 0
# HELP polkadot_parachain_runtime_api_make_runtime_api_request Time spent within `runtime_api::make_runtime_api_request`
# TYPE polkadot_parachain_runtime_api_make_runtime_api_request histogram
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="0.005"} 0
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="0.01"} 0
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="0.025"} 18
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="0.05"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="0.1"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="0.25"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="0.5"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="1"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="2.5"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="5"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="10"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_bucket{le="+Inf"} 22
polkadot_parachain_runtime_api_make_runtime_api_request_sum 0.36860589900000007
polkadot_parachain_runtime_api_make_runtime_api_request_count 22
# HELP polkadot_parachain_runtime_api_requests_total Number of Runtime API requests served.
# TYPE polkadot_parachain_runtime_api_requests_total counter
polkadot_parachain_runtime_api_requests_total{success="cached"} 1
polkadot_parachain_runtime_api_requests_total{success="succeeded"} 22
# HELP polkadot_parachain_statement_distribution_active_leaves_update Time spent within `statement_distribution::active_leaves_update`
# TYPE polkadot_parachain_statement_distribution_active_leaves_update histogram
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="0.005"} 0
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="0.01"} 0
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="0.025"} 0
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="0.05"} 0
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="0.1"} 1
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="0.25"} 1
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="0.5"} 1
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="1"} 1
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="2.5"} 1
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="5"} 1
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="10"} 1
polkadot_parachain_statement_distribution_active_leaves_update_bucket{le="+Inf"} 1
polkadot_parachain_statement_distribution_active_leaves_update_sum 0.065008252
polkadot_parachain_statement_distribution_active_leaves_update_count 1
# HELP polkadot_parachain_statement_distribution_network_bridge_update_v1 Time spent within `statement_distribution::network_bridge_update_v1`
# TYPE polkadot_parachain_statement_distribution_network_bridge_update_v1 histogram
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="0.005"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="0.01"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="0.025"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="0.05"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="0.1"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="0.25"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="0.5"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="1"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="2.5"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="5"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="10"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket{le="+Inf"} 1
polkadot_parachain_statement_distribution_network_bridge_update_v1_sum 0.000001192
polkadot_parachain_statement_distribution_network_bridge_update_v1_count 1
# HELP polkadot_parachain_statement_distribution_sent_requests_total Number of large statement fetching requests sent.
# TYPE polkadot_parachain_statement_distribution_sent_requests_total counter
polkadot_parachain_statement_distribution_sent_requests_total 0
# HELP polkadot_parachain_statement_distribution_share Time spent within `statement_distribution::share`
# TYPE polkadot_parachain_statement_distribution_share histogram
polkadot_parachain_statement_distribution_share_bucket{le="0.005"} 0
polkadot_parachain_statement_distribution_share_bucket{le="0.01"} 0
polkadot_parachain_statement_distribution_share_bucket{le="0.025"} 0
polkadot_parachain_statement_distribution_share_bucket{le="0.05"} 0
polkadot_parachain_statement_distribution_share_bucket{le="0.1"} 0
polkadot_parachain_statement_distribution_share_bucket{le="0.25"} 0
polkadot_parachain_statement_distribution_share_bucket{le="0.5"} 0
polkadot_parachain_statement_distribution_share_bucket{le="1"} 0
polkadot_parachain_statement_distribution_share_bucket{le="2.5"} 0
polkadot_parachain_statement_distribution_share_bucket{le="5"} 0
polkadot_parachain_statement_distribution_share_bucket{le="10"} 0
polkadot_parachain_statement_distribution_share_bucket{le="+Inf"} 0
polkadot_parachain_statement_distribution_share_sum 0
polkadot_parachain_statement_distribution_share_count 0
# HELP polkadot_parachain_statements_distributed_total Number of candidate validity statements distributed to other peers.
# TYPE polkadot_parachain_statements_distributed_total counter
polkadot_parachain_statements_distributed_total 0
# HELP polkadot_parachain_subsystem_bounded_received Number of elements received by subsystems' bounded queues
# TYPE polkadot_parachain_subsystem_bounded_received gauge
polkadot_parachain_subsystem_bounded_received{subsystem_name="BitfieldSigning"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="CandidateBacking"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="Provisioning"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="approval-distribution-subsystem"} 1
polkadot_parachain_subsystem_bounded_received{subsystem_name="approval-voting-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="availability-distribution-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="availability-recovery-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="availability-store-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="bitfield-distribution-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="candidate-validation-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="chain-api-subsystem"} 3
polkadot_parachain_subsystem_bounded_received{subsystem_name="chain-selection-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="collation-generation-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="collator-protocol-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="dispute-coordinator-subsystem"} 1
polkadot_parachain_subsystem_bounded_received{subsystem_name="dispute-distribution-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="dispute-participation-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="gossip-support-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="network-bridge-subsystem"} 0
polkadot_parachain_subsystem_bounded_received{subsystem_name="runtime-api-subsystem"} 23
polkadot_parachain_subsystem_bounded_received{subsystem_name="statement-distribution-subsystem"} 0
# HELP polkadot_parachain_subsystem_bounded_sent Number of elements sent to subsystems' bounded queues
# TYPE polkadot_parachain_subsystem_bounded_sent gauge
polkadot_parachain_subsystem_bounded_sent{subsystem_name="BitfieldSigning"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="CandidateBacking"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="Provisioning"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="approval-distribution-subsystem"} 1
polkadot_parachain_subsystem_bounded_sent{subsystem_name="approval-voting-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="availability-distribution-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="availability-recovery-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="availability-store-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="bitfield-distribution-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="candidate-validation-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="chain-api-subsystem"} 3
polkadot_parachain_subsystem_bounded_sent{subsystem_name="chain-selection-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="collation-generation-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="collator-protocol-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="dispute-coordinator-subsystem"} 1
polkadot_parachain_subsystem_bounded_sent{subsystem_name="dispute-distribution-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="dispute-participation-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="gossip-support-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="network-bridge-subsystem"} 0
polkadot_parachain_subsystem_bounded_sent{subsystem_name="runtime-api-subsystem"} 23
polkadot_parachain_subsystem_bounded_sent{subsystem_name="statement-distribution-subsystem"} 0
# HELP polkadot_parachain_subsystem_unbounded_received Number of elements received by subsystems' unbounded queues
# TYPE polkadot_parachain_subsystem_unbounded_received gauge
polkadot_parachain_subsystem_unbounded_received{subsystem_name="BitfieldSigning"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="CandidateBacking"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="Provisioning"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="approval-distribution-subsystem"} 1
polkadot_parachain_subsystem_unbounded_received{subsystem_name="approval-voting-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="availability-distribution-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="availability-recovery-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="availability-store-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="bitfield-distribution-subsystem"} 1
polkadot_parachain_subsystem_unbounded_received{subsystem_name="candidate-validation-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="chain-api-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="chain-selection-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="collation-generation-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="collator-protocol-subsystem"} 1
polkadot_parachain_subsystem_unbounded_received{subsystem_name="dispute-coordinator-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="dispute-distribution-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="dispute-participation-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="gossip-support-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="network-bridge-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="runtime-api-subsystem"} 0
polkadot_parachain_subsystem_unbounded_received{subsystem_name="statement-distribution-subsystem"} 1
# HELP polkadot_parachain_subsystem_unbounded_sent Number of elements sent to subsystems' unbounded queues
# TYPE polkadot_parachain_subsystem_unbounded_sent gauge
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="BitfieldSigning"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="CandidateBacking"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="Provisioning"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="approval-distribution-subsystem"} 1
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="approval-voting-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="availability-distribution-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="availability-recovery-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="availability-store-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="bitfield-distribution-subsystem"} 1
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="candidate-validation-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="chain-api-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="chain-selection-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="collation-generation-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="collator-protocol-subsystem"} 1
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="dispute-coordinator-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="dispute-distribution-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="dispute-participation-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="gossip-support-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="network-bridge-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="runtime-api-subsystem"} 0
polkadot_parachain_subsystem_unbounded_sent{subsystem_name="statement-distribution-subsystem"} 1
# HELP polkadot_parachain_time_approval_db_transaction Time spent writing an approval db transaction.
# TYPE polkadot_parachain_time_approval_db_transaction histogram
polkadot_parachain_time_approval_db_transaction_bucket{le="0.005"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="0.01"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="0.025"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="0.05"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="0.1"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="0.25"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="0.5"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="1"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="2.5"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="5"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="10"} 0
polkadot_parachain_time_approval_db_transaction_bucket{le="+Inf"} 0
polkadot_parachain_time_approval_db_transaction_sum 0
polkadot_parachain_time_approval_db_transaction_count 0
# HELP polkadot_parachain_time_awaiting_approval_voting Time spent awaiting a reply from the Approval Voting Subsystem.
# TYPE polkadot_parachain_time_awaiting_approval_voting histogram
polkadot_parachain_time_awaiting_approval_voting_bucket{le="0.005"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="0.01"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="0.025"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="0.05"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="0.1"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="0.25"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="0.5"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="1"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="2.5"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="5"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="10"} 0
polkadot_parachain_time_awaiting_approval_voting_bucket{le="+Inf"} 0
polkadot_parachain_time_awaiting_approval_voting_sum 0
polkadot_parachain_time_awaiting_approval_voting_count 0
# HELP polkadot_parachain_time_import_pending_now_known Time spent on importing pending assignments and approvals.
# TYPE polkadot_parachain_time_import_pending_now_known histogram
polkadot_parachain_time_import_pending_now_known_bucket{le="0.005"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="0.01"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="0.025"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="0.05"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="0.1"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="0.25"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="0.5"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="1"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="2.5"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="5"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="10"} 0
polkadot_parachain_time_import_pending_now_known_bucket{le="+Inf"} 0
polkadot_parachain_time_import_pending_now_known_sum 0
polkadot_parachain_time_import_pending_now_known_count 0
# HELP polkadot_parachain_time_recover_and_approve Time spent recovering and approving data in approval voting
# TYPE polkadot_parachain_time_recover_and_approve histogram
polkadot_parachain_time_recover_and_approve_bucket{le="0.005"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="0.01"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="0.025"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="0.05"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="0.1"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="0.25"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="0.5"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="1"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="2.5"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="5"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="10"} 0
polkadot_parachain_time_recover_and_approve_bucket{le="+Inf"} 0
polkadot_parachain_time_recover_and_approve_sum 0
polkadot_parachain_time_recover_and_approve_count 0
# HELP polkadot_parachain_time_unify_with_peer Time spent within fn `unify_with_peer`.
# TYPE polkadot_parachain_time_unify_with_peer histogram
polkadot_parachain_time_unify_with_peer_bucket{le="0.005"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="0.01"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="0.025"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="0.05"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="0.1"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="0.25"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="0.5"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="1"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="2.5"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="5"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="10"} 0
polkadot_parachain_time_unify_with_peer_bucket{le="+Inf"} 0
polkadot_parachain_time_unify_with_peer_sum 0
polkadot_parachain_time_unify_with_peer_count 0
# HELP polkadot_parachain_unified_with_peer_total Number of times `unify_with_peer` is called.
# TYPE polkadot_parachain_unified_with_peer_total counter
polkadot_parachain_unified_with_peer_total 0
# HELP polkadot_process_start_time_seconds Number of seconds between the UNIX epoch and the moment the process started
# TYPE polkadot_process_start_time_seconds gauge
polkadot_process_start_time_seconds 1639632247
# HELP polkadot_ready_transactions_number Number of transactions in the ready queue
# TYPE polkadot_ready_transactions_number gauge
polkadot_ready_transactions_number 0
# HELP polkadot_state_cache_bytes State cache size in bytes
# TYPE polkadot_state_cache_bytes gauge
polkadot_state_cache_bytes 770032
# HELP polkadot_state_db_cache_bytes State DB cache in bytes
# TYPE polkadot_state_db_cache_bytes gauge
polkadot_state_db_cache_bytes{subtype="non_canonical"} 227716
polkadot_state_db_cache_bytes{subtype="pinned"} 132
polkadot_state_db_cache_bytes{subtype="pruning"} 3847560
# HELP polkadot_sub_libp2p_connections_closed_total Total number of connections closed, by direction and reason
# TYPE polkadot_sub_libp2p_connections_closed_total counter
polkadot_sub_libp2p_connections_closed_total{direction="in",reason="keep-alive-timeout"} 1
polkadot_sub_libp2p_connections_closed_total{direction="out",reason="transport-error"} 1
# HELP polkadot_sub_libp2p_connections_opened_total Total number of connections opened by direction
# TYPE polkadot_sub_libp2p_connections_opened_total counter
polkadot_sub_libp2p_connections_opened_total{direction="in"} 1
polkadot_sub_libp2p_connections_opened_total{direction="out"} 1
# HELP polkadot_sub_libp2p_distinct_peers_connections_closed_total Total number of connections closed with distinct peers
# TYPE polkadot_sub_libp2p_distinct_peers_connections_closed_total counter
polkadot_sub_libp2p_distinct_peers_connections_closed_total 2
# HELP polkadot_sub_libp2p_distinct_peers_connections_opened_total Total number of connections opened with distinct peers
# TYPE polkadot_sub_libp2p_distinct_peers_connections_opened_total counter
polkadot_sub_libp2p_distinct_peers_connections_opened_total 2
# HELP polkadot_sub_libp2p_incoming_connections_total Total number of incoming connections on the listening sockets
# TYPE polkadot_sub_libp2p_incoming_connections_total counter
polkadot_sub_libp2p_incoming_connections_total 1
# HELP polkadot_sub_libp2p_is_major_syncing Whether the node is performing a major sync or not.
# TYPE polkadot_sub_libp2p_is_major_syncing gauge
polkadot_sub_libp2p_is_major_syncing 0
# HELP polkadot_sub_libp2p_kademlia_query_duration Duration of Kademlia queries per query type
# TYPE polkadot_sub_libp2p_kademlia_query_duration histogram
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="0.5"} 0
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="1"} 28
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="2"} 34
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="4"} 36
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="8"} 36
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="16"} 36
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="32"} 36
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="64"} 36
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="128"} 36
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="256"} 36
polkadot_sub_libp2p_kademlia_query_duration_bucket{type="value-not-found",le="+Inf"} 36
polkadot_sub_libp2p_kademlia_query_duration_sum{type="value-not-found"} 32.596499556000005
polkadot_sub_libp2p_kademlia_query_duration_count{type="value-not-found"} 36
# HELP polkadot_sub_libp2p_kademlia_random_queries_total Number of random Kademlia queries started
# TYPE polkadot_sub_libp2p_kademlia_random_queries_total counter
polkadot_sub_libp2p_kademlia_random_queries_total{protocol="battery_station_relay"} 117
# HELP polkadot_sub_libp2p_kademlia_records_count Number of records in the Kademlia records store
# TYPE polkadot_sub_libp2p_kademlia_records_count gauge
polkadot_sub_libp2p_kademlia_records_count{protocol="battery_station_relay"} 0
# HELP polkadot_sub_libp2p_kademlia_records_sizes_total Total size of all the records in the Kademlia records store
# TYPE polkadot_sub_libp2p_kademlia_records_sizes_total gauge
polkadot_sub_libp2p_kademlia_records_sizes_total{protocol="battery_station_relay"} 0
# HELP polkadot_sub_libp2p_kbuckets_num_nodes Number of nodes per kbucket per Kademlia instance
# TYPE polkadot_sub_libp2p_kbuckets_num_nodes gauge
polkadot_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="252",protocol="battery_station_relay"} 1
polkadot_sub_libp2p_kbuckets_num_nodes{lower_ilog2_bucket_bound="255",protocol="battery_station_relay"} 1
# HELP polkadot_sub_libp2p_listeners_errors_total Total number of non-fatal errors reported by a listener
# TYPE polkadot_sub_libp2p_listeners_errors_total counter
polkadot_sub_libp2p_listeners_errors_total 0
# HELP polkadot_sub_libp2p_listeners_local_addresses Number of local addresses we're listening on
# TYPE polkadot_sub_libp2p_listeners_local_addresses gauge
polkadot_sub_libp2p_listeners_local_addresses 5
# HELP polkadot_sub_libp2p_network_bytes_total Total bandwidth usage
# TYPE polkadot_sub_libp2p_network_bytes_total counter
polkadot_sub_libp2p_network_bytes_total{direction="in"} 4429
polkadot_sub_libp2p_network_bytes_total{direction="out"} 5031
# HELP polkadot_sub_libp2p_out_events_events_total Number of broadcast network events that have been sent or received across all channels
# TYPE polkadot_sub_libp2p_out_events_events_total counter
polkadot_sub_libp2p_out_events_events_total{action="received",event_name="dht",name="authority-discovery"} 36
polkadot_sub_libp2p_out_events_events_total{action="received",event_name="dht",name="network-gossip"} 36
polkadot_sub_libp2p_out_events_events_total{action="received",event_name="dht",name="polkadot-network-bridge"} 36
polkadot_sub_libp2p_out_events_events_total{action="received",event_name="dht",name="transactions-handler"} 36
polkadot_sub_libp2p_out_events_events_total{action="sent",event_name="dht",name="authority-discovery"} 36
polkadot_sub_libp2p_out_events_events_total{action="sent",event_name="dht",name="network-gossip"} 36
polkadot_sub_libp2p_out_events_events_total{action="sent",event_name="dht",name="polkadot-network-bridge"} 36
polkadot_sub_libp2p_out_events_events_total{action="sent",event_name="dht",name="transactions-handler"} 36
# HELP polkadot_sub_libp2p_out_events_num_channels Number of internal active channels that broadcast network events
# TYPE polkadot_sub_libp2p_out_events_num_channels gauge
polkadot_sub_libp2p_out_events_num_channels{name="authority-discovery"} 1
polkadot_sub_libp2p_out_events_num_channels{name="network-gossip"} 1
polkadot_sub_libp2p_out_events_num_channels{name="polkadot-network-bridge"} 1
polkadot_sub_libp2p_out_events_num_channels{name="transactions-handler"} 1
# HELP polkadot_sub_libp2p_peers_count Number of connected peers
# TYPE polkadot_sub_libp2p_peers_count gauge
polkadot_sub_libp2p_peers_count 0
# HELP polkadot_sub_libp2p_peerset_num_discovered Number of nodes stored in the peerset manager
# TYPE polkadot_sub_libp2p_peerset_num_discovered gauge
polkadot_sub_libp2p_peerset_num_discovered 2
# HELP polkadot_sub_libp2p_peerset_num_requested Number of nodes that the peerset manager wants us to be connected to
# TYPE polkadot_sub_libp2p_peerset_num_requested gauge
polkadot_sub_libp2p_peerset_num_requested 2
# HELP polkadot_sub_libp2p_pending_connections Number of connections in the process of being established
# TYPE polkadot_sub_libp2p_pending_connections gauge
polkadot_sub_libp2p_pending_connections 0
# HELP polkadot_sub_libp2p_pending_connections_errors_total Total number of pending connection errors
# TYPE polkadot_sub_libp2p_pending_connections_errors_total counter
polkadot_sub_libp2p_pending_connections_errors_total{reason="transport-error"} 7131
# HELP polkadot_sub_txpool_block_transactions_pruned Total number of transactions that was requested to be pruned by block events
# TYPE polkadot_sub_txpool_block_transactions_pruned counter
polkadot_sub_txpool_block_transactions_pruned 0
# HELP polkadot_sub_txpool_block_transactions_resubmitted Total number of transactions that was requested to be resubmitted by block events
# TYPE polkadot_sub_txpool_block_transactions_resubmitted counter
polkadot_sub_txpool_block_transactions_resubmitted 0
# HELP polkadot_sub_txpool_submitted_transactions Total number of transactions submitted
# TYPE polkadot_sub_txpool_submitted_transactions counter
polkadot_sub_txpool_submitted_transactions 0
# HELP polkadot_sub_txpool_validations_finished Total number of transactions that finished validation
# TYPE polkadot_sub_txpool_validations_finished counter
polkadot_sub_txpool_validations_finished 0
# HELP polkadot_sub_txpool_validations_invalid Total number of transactions that were removed from the pool as invalid
# TYPE polkadot_sub_txpool_validations_invalid counter
polkadot_sub_txpool_validations_invalid 0
# HELP polkadot_sub_txpool_validations_scheduled Total number of transactions scheduled for validation
# TYPE polkadot_sub_txpool_validations_scheduled counter
polkadot_sub_txpool_validations_scheduled 0
# HELP polkadot_sync_extra_justifications Number of extra justifications requests
# TYPE polkadot_sync_extra_justifications gauge
polkadot_sync_extra_justifications{status="active"} 0
polkadot_sync_extra_justifications{status="failed"} 0
polkadot_sync_extra_justifications{status="importing"} 0
polkadot_sync_extra_justifications{status="pending"} 0
# HELP polkadot_sync_fork_targets Number of fork sync targets
# TYPE polkadot_sync_fork_targets gauge
polkadot_sync_fork_targets 0
# HELP polkadot_sync_peers Number of peers we sync with
# TYPE polkadot_sync_peers gauge
polkadot_sync_peers 0
# HELP polkadot_sync_propagated_transactions Number of transactions propagated to at least one peer
# TYPE polkadot_sync_propagated_transactions counter
polkadot_sync_propagated_transactions 0
# HELP polkadot_sync_queued_blocks Number of blocks in import queue
# TYPE polkadot_sync_queued_blocks gauge
polkadot_sync_queued_blocks 0
# HELP polkadot_tasks_ended_total Total number of tasks for which Future::poll has returned Ready(()) or panicked
# TYPE polkadot_tasks_ended_total counter
polkadot_tasks_ended_total{reason="finished",task_name="BitfieldSigning"} 0
polkadot_tasks_ended_total{reason="finished",task_name="BitfieldSigningJob"} 1
polkadot_tasks_ended_total{reason="finished",task_name="CandidateBacking"} 0
polkadot_tasks_ended_total{reason="finished",task_name="CandidateBackingJob"} 0
polkadot_tasks_ended_total{reason="finished",task_name="Provisioning"} 0
polkadot_tasks_ended_total{reason="finished",task_name="ProvisioningJob"} 0
polkadot_tasks_ended_total{reason="finished",task_name="approval-distribution-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="approval-voting-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="authority-discovery-worker"} 0
polkadot_tasks_ended_total{reason="finished",task_name="availability-distribution-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="availability-recovery-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="availability-store-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="basic-block-import-worker"} 0
polkadot_tasks_ended_total{reason="finished",task_name="bitfield-distribution-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="block_request_handler"} 0
polkadot_tasks_ended_total{reason="finished",task_name="candidate-validation-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="chain-api-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="chain-selection-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="chunk-receiver"} 0
polkadot_tasks_ended_total{reason="finished",task_name="collation-generation-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="collator-protocol-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="dispute-coordinator-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="dispute-distribution-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="dispute-participation-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="disputes-receiver"} 0
polkadot_tasks_ended_total{reason="finished",task_name="gossip-support-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="grandpa-voter"} 0
polkadot_tasks_ended_total{reason="finished",task_name="informant"} 0
polkadot_tasks_ended_total{reason="finished",task_name="large-statement-responder"} 0
polkadot_tasks_ended_total{reason="finished",task_name="libp2p-node"} 7133
polkadot_tasks_ended_total{reason="finished",task_name="light_client_request_handler"} 0
polkadot_tasks_ended_total{reason="finished",task_name="metrics_metronome"} 0
polkadot_tasks_ended_total{reason="finished",task_name="network-bridge-network-worker"} 0
polkadot_tasks_ended_total{reason="finished",task_name="network-bridge-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="network-transactions-handler"} 0
polkadot_tasks_ended_total{reason="finished",task_name="network-worker"} 0
polkadot_tasks_ended_total{reason="finished",task_name="on-transaction-imported"} 0
polkadot_tasks_ended_total{reason="finished",task_name="overseer"} 0
polkadot_tasks_ended_total{reason="finished",task_name="polkadot-runtime-api-request"} 22
polkadot_tasks_ended_total{reason="finished",task_name="pov-receiver"} 0
polkadot_tasks_ended_total{reason="finished",task_name="prometheus-endpoint"} 0
polkadot_tasks_ended_total{reason="finished",task_name="pvf-validation-host"} 0
polkadot_tasks_ended_total{reason="finished",task_name="runtime-api-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="state_request_handler"} 0
polkadot_tasks_ended_total{reason="finished",task_name="statement-distribution-subsystem"} 0
polkadot_tasks_ended_total{reason="finished",task_name="telemetry-periodic-send"} 0
polkadot_tasks_ended_total{reason="finished",task_name="transaction-pool-task-0"} 0
polkadot_tasks_ended_total{reason="finished",task_name="transaction-pool-task-1"} 0
polkadot_tasks_ended_total{reason="finished",task_name="txpool-background"} 0
polkadot_tasks_ended_total{reason="finished",task_name="txpool-notifications"} 0
polkadot_tasks_ended_total{reason="finished",task_name="warp_sync_request_handler"} 0
# HELP polkadot_tasks_polling_duration Duration in seconds of each invocation of Future::poll
# TYPE polkadot_tasks_polling_duration histogram
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="0.001"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="0.004"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="0.016"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="0.064"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="0.256"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="1.024"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="4.096"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="16.384"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="65.536"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigning",le="+Inf"} 5
polkadot_tasks_polling_duration_sum{task_name="BitfieldSigning"} 0.000190671
polkadot_tasks_polling_duration_count{task_name="BitfieldSigning"} 5
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="0.001"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="0.004"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="0.016"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="0.064"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="0.256"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="BitfieldSigningJob",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="BitfieldSigningJob"} 0.000057289
polkadot_tasks_polling_duration_count{task_name="BitfieldSigningJob"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="0.001"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="0.004"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="0.016"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="0.064"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="0.256"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBacking",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="CandidateBacking"} 0.000092235
polkadot_tasks_polling_duration_count{task_name="CandidateBacking"} 3
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="0.001"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="0.004"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="0.016"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="0.064"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="0.256"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="1.024"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="4.096"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="16.384"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="65.536"} 5
polkadot_tasks_polling_duration_bucket{task_name="CandidateBackingJob",le="+Inf"} 5
polkadot_tasks_polling_duration_sum{task_name="CandidateBackingJob"} 0.000366054
polkadot_tasks_polling_duration_count{task_name="CandidateBackingJob"} 5
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="0.001"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="0.004"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="0.016"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="0.064"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="0.256"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="Provisioning",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="Provisioning"} 0.000136888
polkadot_tasks_polling_duration_count{task_name="Provisioning"} 3
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="0.001"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="0.004"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="0.016"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="0.064"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="0.256"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="1.024"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="4.096"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="16.384"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="65.536"} 2
polkadot_tasks_polling_duration_bucket{task_name="ProvisioningJob",le="+Inf"} 2
polkadot_tasks_polling_duration_sum{task_name="ProvisioningJob"} 0.000021491
polkadot_tasks_polling_duration_count{task_name="ProvisioningJob"} 2
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="0.001"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="0.004"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="0.016"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="0.064"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="0.256"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="1.024"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="4.096"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="16.384"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="65.536"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-distribution-subsystem",le="+Inf"} 4
polkadot_tasks_polling_duration_sum{task_name="approval-distribution-subsystem"} 0.000081825
polkadot_tasks_polling_duration_count{task_name="approval-distribution-subsystem"} 4
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="0.001"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="0.004"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="0.016"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="0.064"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="0.256"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="1.024"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="4.096"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="16.384"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="65.536"} 10
polkadot_tasks_polling_duration_bucket{task_name="approval-voting-subsystem",le="+Inf"} 10
polkadot_tasks_polling_duration_sum{task_name="approval-voting-subsystem"} 0.000648947
polkadot_tasks_polling_duration_count{task_name="approval-voting-subsystem"} 10
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="0.001"} 139
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="0.004"} 139
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="0.016"} 139
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="0.064"} 157
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="0.256"} 157
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="1.024"} 157
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="4.096"} 157
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="16.384"} 157
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="65.536"} 157
polkadot_tasks_polling_duration_bucket{task_name="authority-discovery-worker",le="+Inf"} 157
polkadot_tasks_polling_duration_sum{task_name="authority-discovery-worker"} 0.7076655319999997
polkadot_tasks_polling_duration_count{task_name="authority-discovery-worker"} 157
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="0.001"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="0.004"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="0.016"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="0.064"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="0.256"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-distribution-subsystem",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="availability-distribution-subsystem"} 0.00027938899999999995
polkadot_tasks_polling_duration_count{task_name="availability-distribution-subsystem"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="0.001"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="0.004"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="0.016"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="0.064"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="0.256"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-recovery-subsystem",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="availability-recovery-subsystem"} 0.0004912299999999999
polkadot_tasks_polling_duration_count{task_name="availability-recovery-subsystem"} 3
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="0.001"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="0.004"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="0.016"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="0.064"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="0.256"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="1.024"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="4.096"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="16.384"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="65.536"} 27
polkadot_tasks_polling_duration_bucket{task_name="availability-store-subsystem",le="+Inf"} 27
polkadot_tasks_polling_duration_sum{task_name="availability-store-subsystem"} 0.0019516000000000002
polkadot_tasks_polling_duration_count{task_name="availability-store-subsystem"} 27
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="basic-block-import-worker",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="basic-block-import-worker"} 0.000494406
polkadot_tasks_polling_duration_count{task_name="basic-block-import-worker"} 1
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="0.001"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="0.004"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="0.016"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="0.064"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="0.256"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="1.024"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="4.096"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="16.384"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="65.536"} 5
polkadot_tasks_polling_duration_bucket{task_name="bitfield-distribution-subsystem",le="+Inf"} 5
polkadot_tasks_polling_duration_sum{task_name="bitfield-distribution-subsystem"} 0.000082057
polkadot_tasks_polling_duration_count{task_name="bitfield-distribution-subsystem"} 5
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="block_request_handler",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="block_request_handler"} 0.000215829
polkadot_tasks_polling_duration_count{task_name="block_request_handler"} 1
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="0.001"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="0.004"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="0.016"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="0.064"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="0.256"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="1.024"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="4.096"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="16.384"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="65.536"} 2
polkadot_tasks_polling_duration_bucket{task_name="candidate-validation-subsystem",le="+Inf"} 2
polkadot_tasks_polling_duration_sum{task_name="candidate-validation-subsystem"} 0.00031876399999999997
polkadot_tasks_polling_duration_count{task_name="candidate-validation-subsystem"} 2
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="0.001"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="0.004"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="0.016"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="0.064"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="0.256"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="1.024"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="4.096"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="16.384"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="65.536"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-api-subsystem",le="+Inf"} 6
polkadot_tasks_polling_duration_sum{task_name="chain-api-subsystem"} 0.000070844
polkadot_tasks_polling_duration_count{task_name="chain-api-subsystem"} 6
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="0.001"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="0.004"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="0.016"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="0.064"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="0.256"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="chain-selection-subsystem",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="chain-selection-subsystem"} 0.000248079
polkadot_tasks_polling_duration_count{task_name="chain-selection-subsystem"} 3
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="chunk-receiver",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="chunk-receiver"} 0.000001583
polkadot_tasks_polling_duration_count{task_name="chunk-receiver"} 1
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="0.001"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="0.004"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="0.016"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="0.064"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="0.256"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="1.024"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="4.096"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="16.384"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="65.536"} 2
polkadot_tasks_polling_duration_bucket{task_name="collation-generation-subsystem",le="+Inf"} 2
polkadot_tasks_polling_duration_sum{task_name="collation-generation-subsystem"} 0.00024033500000000002
polkadot_tasks_polling_duration_count{task_name="collation-generation-subsystem"} 2
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="0.001"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="0.004"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="0.016"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="0.064"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="0.256"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="1.024"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="4.096"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="16.384"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="65.536"} 4
polkadot_tasks_polling_duration_bucket{task_name="collator-protocol-subsystem",le="+Inf"} 4
polkadot_tasks_polling_duration_sum{task_name="collator-protocol-subsystem"} 0.00005821
polkadot_tasks_polling_duration_count{task_name="collator-protocol-subsystem"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="0.001"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="0.004"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="0.016"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="0.064"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="0.256"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-coordinator-subsystem",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="dispute-coordinator-subsystem"} 0.000016681
polkadot_tasks_polling_duration_count{task_name="dispute-coordinator-subsystem"} 3
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="0.001"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="0.004"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="0.016"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="0.064"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="0.256"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="1.024"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="4.096"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="16.384"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="65.536"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-distribution-subsystem",le="+Inf"} 4
polkadot_tasks_polling_duration_sum{task_name="dispute-distribution-subsystem"} 0.000089641
polkadot_tasks_polling_duration_count{task_name="dispute-distribution-subsystem"} 4
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="0.001"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="0.004"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="0.016"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="0.064"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="0.256"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="1.024"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="4.096"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="16.384"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="65.536"} 2
polkadot_tasks_polling_duration_bucket{task_name="dispute-participation-subsystem",le="+Inf"} 2
polkadot_tasks_polling_duration_sum{task_name="dispute-participation-subsystem"} 0.000008697
polkadot_tasks_polling_duration_count{task_name="dispute-participation-subsystem"} 2
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="disputes-receiver",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="disputes-receiver"} 0.000002615
polkadot_tasks_polling_duration_count{task_name="disputes-receiver"} 1
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="0.001"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="0.004"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="0.016"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="0.064"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="0.256"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="1.024"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="4.096"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="16.384"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="65.536"} 4
polkadot_tasks_polling_duration_bucket{task_name="gossip-support-subsystem",le="+Inf"} 4
polkadot_tasks_polling_duration_sum{task_name="gossip-support-subsystem"} 0.000057718999999999994
polkadot_tasks_polling_duration_count{task_name="gossip-support-subsystem"} 4
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.001"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.004"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.016"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.064"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="0.256"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="1.024"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="4.096"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="16.384"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="65.536"} 7523
polkadot_tasks_polling_duration_bucket{task_name="grandpa-voter",le="+Inf"} 7523
polkadot_tasks_polling_duration_sum{task_name="grandpa-voter"} 0.19800640899999933
polkadot_tasks_polling_duration_count{task_name="grandpa-voter"} 7523
polkadot_tasks_polling_duration_bucket{task_name="informant",le="0.001"} 2350
polkadot_tasks_polling_duration_bucket{task_name="informant",le="0.004"} 2673
polkadot_tasks_polling_duration_bucket{task_name="informant",le="0.016"} 2673
polkadot_tasks_polling_duration_bucket{task_name="informant",le="0.064"} 2673
polkadot_tasks_polling_duration_bucket{task_name="informant",le="0.256"} 2673
polkadot_tasks_polling_duration_bucket{task_name="informant",le="1.024"} 2673
polkadot_tasks_polling_duration_bucket{task_name="informant",le="4.096"} 2673
polkadot_tasks_polling_duration_bucket{task_name="informant",le="16.384"} 2673
polkadot_tasks_polling_duration_bucket{task_name="informant",le="65.536"} 2673
polkadot_tasks_polling_duration_bucket{task_name="informant",le="+Inf"} 2673
polkadot_tasks_polling_duration_sum{task_name="informant"} 1.2876430650000017
polkadot_tasks_polling_duration_count{task_name="informant"} 2673
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="large-statement-responder",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="large-statement-responder"} 0.000001082
polkadot_tasks_polling_duration_count{task_name="large-statement-responder"} 1
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.001"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.004"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.016"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.064"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="0.256"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="1.024"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="4.096"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="16.384"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="65.536"} 14341
polkadot_tasks_polling_duration_bucket{task_name="libp2p-node",le="+Inf"} 14341
polkadot_tasks_polling_duration_sum{task_name="libp2p-node"} 2.4585548890000095
polkadot_tasks_polling_duration_count{task_name="libp2p-node"} 14341
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="light_client_request_handler",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="light_client_request_handler"} 0.000000741
polkadot_tasks_polling_duration_count{task_name="light_client_request_handler"} 1
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="0.001"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="0.004"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="0.016"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="0.064"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="0.256"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="1.024"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="4.096"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="16.384"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="65.536"} 7060
polkadot_tasks_polling_duration_bucket{task_name="metrics_metronome",le="+Inf"} 7060
polkadot_tasks_polling_duration_sum{task_name="metrics_metronome"} 0.2287300549999992
polkadot_tasks_polling_duration_count{task_name="metrics_metronome"} 7060
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="0.001"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="0.004"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="0.016"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="0.064"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="0.256"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="1.024"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="4.096"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="16.384"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="65.536"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-network-worker",le="+Inf"} 19
polkadot_tasks_polling_duration_sum{task_name="network-bridge-network-worker"} 0.000147655
polkadot_tasks_polling_duration_count{task_name="network-bridge-network-worker"} 19
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="0.001"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="0.004"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="0.016"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="0.064"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="0.256"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="1.024"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="4.096"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="16.384"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="65.536"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-bridge-subsystem",le="+Inf"} 2
polkadot_tasks_polling_duration_sum{task_name="network-bridge-subsystem"} 0.000285199
polkadot_tasks_polling_duration_count{task_name="network-bridge-subsystem"} 2
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.001"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.004"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.016"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.064"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="0.256"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="1.024"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="4.096"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="16.384"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="65.536"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-transactions-handler",le="+Inf"} 2337
polkadot_tasks_polling_duration_sum{task_name="network-transactions-handler"} 0.03346039800000002
polkadot_tasks_polling_duration_count{task_name="network-transactions-handler"} 2337
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="0.001"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="0.004"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="0.016"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="0.064"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="0.256"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="1.024"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="4.096"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="16.384"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="65.536"} 86114
polkadot_tasks_polling_duration_bucket{task_name="network-worker",le="+Inf"} 86114
polkadot_tasks_polling_duration_sum{task_name="network-worker"} 2.280962052999976
polkadot_tasks_polling_duration_count{task_name="network-worker"} 86114
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="on-transaction-imported",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="on-transaction-imported"} 0.000153731
polkadot_tasks_polling_duration_count{task_name="on-transaction-imported"} 1
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="0.001"} 2
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="0.004"} 2
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="0.016"} 2
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="0.064"} 2
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="0.256"} 2
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="overseer",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="overseer"} 0.697790373
polkadot_tasks_polling_duration_count{task_name="overseer"} 3
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="0.001"} 0
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="0.004"} 0
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="0.016"} 15
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="0.064"} 22
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="0.256"} 22
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="1.024"} 22
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="4.096"} 22
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="16.384"} 22
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="65.536"} 22
polkadot_tasks_polling_duration_bucket{task_name="polkadot-runtime-api-request",le="+Inf"} 22
polkadot_tasks_polling_duration_sum{task_name="polkadot-runtime-api-request"} 0.3686956260000001
polkadot_tasks_polling_duration_count{task_name="polkadot-runtime-api-request"} 22
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="pov-receiver",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="pov-receiver"} 0.000002375
polkadot_tasks_polling_duration_count{task_name="pov-receiver"} 1
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.001"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.004"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.016"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.064"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="0.256"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="1.024"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="4.096"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="16.384"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="65.536"} 3
polkadot_tasks_polling_duration_bucket{task_name="prometheus-endpoint",le="+Inf"} 3
polkadot_tasks_polling_duration_sum{task_name="prometheus-endpoint"} 0.00052919
polkadot_tasks_polling_duration_count{task_name="prometheus-endpoint"} 3
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="0.001"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="0.004"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="0.016"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="0.064"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="0.256"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="1.024"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="4.096"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="16.384"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="65.536"} 6
polkadot_tasks_polling_duration_bucket{task_name="pvf-validation-host",le="+Inf"} 6
polkadot_tasks_polling_duration_sum{task_name="pvf-validation-host"} 0.000049613
polkadot_tasks_polling_duration_count{task_name="pvf-validation-host"} 6
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="0.001"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="0.004"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="0.016"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="0.064"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="0.256"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="1.024"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="4.096"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="16.384"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="65.536"} 41
polkadot_tasks_polling_duration_bucket{task_name="runtime-api-subsystem",le="+Inf"} 41
polkadot_tasks_polling_duration_sum{task_name="runtime-api-subsystem"} 0.0008278759999999995
polkadot_tasks_polling_duration_count{task_name="runtime-api-subsystem"} 41
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="state_request_handler",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="state_request_handler"} 0.000000982
polkadot_tasks_polling_duration_count{task_name="state_request_handler"} 1
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="0.001"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="0.004"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="0.016"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="0.064"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="0.256"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="1.024"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="4.096"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="16.384"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="65.536"} 5
polkadot_tasks_polling_duration_bucket{task_name="statement-distribution-subsystem",le="+Inf"} 5
polkadot_tasks_polling_duration_sum{task_name="statement-distribution-subsystem"} 0.000389798
polkadot_tasks_polling_duration_count{task_name="statement-distribution-subsystem"} 5
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.001"} 2538
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.004"} 2684
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.016"} 2684
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.064"} 2684
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="0.256"} 2684
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="1.024"} 2684
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="4.096"} 2684
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="16.384"} 2684
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="65.536"} 2684
polkadot_tasks_polling_duration_bucket{task_name="telemetry-periodic-send",le="+Inf"} 2684
polkadot_tasks_polling_duration_sum{task_name="telemetry-periodic-send"} 1.2528444749999985
polkadot_tasks_polling_duration_count{task_name="telemetry-periodic-send"} 2684
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-0",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="transaction-pool-task-0"} 0.000378548
polkadot_tasks_polling_duration_count{task_name="transaction-pool-task-0"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="transaction-pool-task-1",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="transaction-pool-task-1"} 0.000611508
polkadot_tasks_polling_duration_count{task_name="transaction-pool-task-1"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="0.001"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="0.004"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="0.016"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="0.064"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="0.256"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="1.024"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="4.096"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="16.384"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="65.536"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-background",le="+Inf"} 33518
polkadot_tasks_polling_duration_sum{task_name="txpool-background"} 0.2975580010000018
polkadot_tasks_polling_duration_count{task_name="txpool-background"} 33518
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="txpool-notifications",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="txpool-notifications"} 0.000010941
polkadot_tasks_polling_duration_count{task_name="txpool-notifications"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.001"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.004"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.016"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.064"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="0.256"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="1.024"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="4.096"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="16.384"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="65.536"} 1
polkadot_tasks_polling_duration_bucket{task_name="warp_sync_request_handler",le="+Inf"} 1
polkadot_tasks_polling_duration_sum{task_name="warp_sync_request_handler"} 0.000054022
polkadot_tasks_polling_duration_count{task_name="warp_sync_request_handler"} 1
# HELP polkadot_tasks_polling_started_total Total number of times we started invoking Future::poll
# TYPE polkadot_tasks_polling_started_total counter
polkadot_tasks_polling_started_total{task_name="BitfieldSigning"} 5
polkadot_tasks_polling_started_total{task_name="BitfieldSigningJob"} 3
polkadot_tasks_polling_started_total{task_name="CandidateBacking"} 3
polkadot_tasks_polling_started_total{task_name="CandidateBackingJob"} 5
polkadot_tasks_polling_started_total{task_name="Provisioning"} 3
polkadot_tasks_polling_started_total{task_name="ProvisioningJob"} 2
polkadot_tasks_polling_started_total{task_name="approval-distribution-subsystem"} 4
polkadot_tasks_polling_started_total{task_name="approval-voting-subsystem"} 10
polkadot_tasks_polling_started_total{task_name="authority-discovery-worker"} 157
polkadot_tasks_polling_started_total{task_name="availability-distribution-subsystem"} 3
polkadot_tasks_polling_started_total{task_name="availability-recovery-subsystem"} 3
polkadot_tasks_polling_started_total{task_name="availability-store-subsystem"} 27
polkadot_tasks_polling_started_total{task_name="basic-block-import-worker"} 1
polkadot_tasks_polling_started_total{task_name="bitfield-distribution-subsystem"} 5
polkadot_tasks_polling_started_total{task_name="block_request_handler"} 1
polkadot_tasks_polling_started_total{task_name="candidate-validation-subsystem"} 2
polkadot_tasks_polling_started_total{task_name="chain-api-subsystem"} 6
polkadot_tasks_polling_started_total{task_name="chain-selection-subsystem"} 3
polkadot_tasks_polling_started_total{task_name="chunk-receiver"} 1
polkadot_tasks_polling_started_total{task_name="collation-generation-subsystem"} 2
polkadot_tasks_polling_started_total{task_name="collator-protocol-subsystem"} 4
polkadot_tasks_polling_started_total{task_name="dispute-coordinator-subsystem"} 3
polkadot_tasks_polling_started_total{task_name="dispute-distribution-subsystem"} 4
polkadot_tasks_polling_started_total{task_name="dispute-participation-subsystem"} 2
polkadot_tasks_polling_started_total{task_name="disputes-receiver"} 1
polkadot_tasks_polling_started_total{task_name="gossip-support-subsystem"} 4
polkadot_tasks_polling_started_total{task_name="grandpa-voter"} 7523
polkadot_tasks_polling_started_total{task_name="informant"} 2673
polkadot_tasks_polling_started_total{task_name="large-statement-responder"} 1
polkadot_tasks_polling_started_total{task_name="libp2p-node"} 14341
polkadot_tasks_polling_started_total{task_name="light_client_request_handler"} 1
polkadot_tasks_polling_started_total{task_name="metrics_metronome"} 7060
polkadot_tasks_polling_started_total{task_name="network-bridge-network-worker"} 19
polkadot_tasks_polling_started_total{task_name="network-bridge-subsystem"} 2
polkadot_tasks_polling_started_total{task_name="network-transactions-handler"} 2337
polkadot_tasks_polling_started_total{task_name="network-worker"} 86114
polkadot_tasks_polling_started_total{task_name="on-transaction-imported"} 1
polkadot_tasks_polling_started_total{task_name="overseer"} 3
polkadot_tasks_polling_started_total{task_name="polkadot-runtime-api-request"} 22
polkadot_tasks_polling_started_total{task_name="pov-receiver"} 1
polkadot_tasks_polling_started_total{task_name="prometheus-endpoint"} 3
polkadot_tasks_polling_started_total{task_name="pvf-validation-host"} 6
polkadot_tasks_polling_started_total{task_name="runtime-api-subsystem"} 41
polkadot_tasks_polling_started_total{task_name="state_request_handler"} 1
polkadot_tasks_polling_started_total{task_name="statement-distribution-subsystem"} 5
polkadot_tasks_polling_started_total{task_name="telemetry-periodic-send"} 2684
polkadot_tasks_polling_started_total{task_name="transaction-pool-task-0"} 1
polkadot_tasks_polling_started_total{task_name="transaction-pool-task-1"} 1
polkadot_tasks_polling_started_total{task_name="txpool-background"} 33518
polkadot_tasks_polling_started_total{task_name="txpool-notifications"} 1
polkadot_tasks_polling_started_total{task_name="warp_sync_request_handler"} 1
# HELP polkadot_tasks_spawned_total Total number of tasks that have been spawned on the Service
# TYPE polkadot_tasks_spawned_total counter
polkadot_tasks_spawned_total{task_name="BitfieldSigning"} 1
polkadot_tasks_spawned_total{task_name="BitfieldSigningJob"} 1
polkadot_tasks_spawned_total{task_name="CandidateBacking"} 1
polkadot_tasks_spawned_total{task_name="CandidateBackingJob"} 1
polkadot_tasks_spawned_total{task_name="Provisioning"} 1
polkadot_tasks_spawned_total{task_name="ProvisioningJob"} 1
polkadot_tasks_spawned_total{task_name="approval-distribution-subsystem"} 1
polkadot_tasks_spawned_total{task_name="approval-voting-subsystem"} 1
polkadot_tasks_spawned_total{task_name="authority-discovery-worker"} 1
polkadot_tasks_spawned_total{task_name="availability-distribution-subsystem"} 1
polkadot_tasks_spawned_total{task_name="availability-recovery-subsystem"} 1
polkadot_tasks_spawned_total{task_name="availability-store-subsystem"} 1
polkadot_tasks_spawned_total{task_name="basic-block-import-worker"} 1
polkadot_tasks_spawned_total{task_name="bitfield-distribution-subsystem"} 1
polkadot_tasks_spawned_total{task_name="block_request_handler"} 1
polkadot_tasks_spawned_total{task_name="candidate-validation-subsystem"} 1
polkadot_tasks_spawned_total{task_name="chain-api-subsystem"} 1
polkadot_tasks_spawned_total{task_name="chain-selection-subsystem"} 1
polkadot_tasks_spawned_total{task_name="chunk-receiver"} 1
polkadot_tasks_spawned_total{task_name="collation-generation-subsystem"} 1
polkadot_tasks_spawned_total{task_name="collator-protocol-subsystem"} 1
polkadot_tasks_spawned_total{task_name="dispute-coordinator-subsystem"} 1
polkadot_tasks_spawned_total{task_name="dispute-distribution-subsystem"} 1
polkadot_tasks_spawned_total{task_name="dispute-participation-subsystem"} 1
polkadot_tasks_spawned_total{task_name="disputes-receiver"} 1
polkadot_tasks_spawned_total{task_name="gossip-support-subsystem"} 1
polkadot_tasks_spawned_total{task_name="grandpa-voter"} 1
polkadot_tasks_spawned_total{task_name="informant"} 1
polkadot_tasks_spawned_total{task_name="large-statement-responder"} 1
polkadot_tasks_spawned_total{task_name="libp2p-node"} 7133
polkadot_tasks_spawned_total{task_name="light_client_request_handler"} 1
polkadot_tasks_spawned_total{task_name="metrics_metronome"} 1
polkadot_tasks_spawned_total{task_name="network-bridge-network-worker"} 1
polkadot_tasks_spawned_total{task_name="network-bridge-subsystem"} 1
polkadot_tasks_spawned_total{task_name="network-transactions-handler"} 1
polkadot_tasks_spawned_total{task_name="network-worker"} 1
polkadot_tasks_spawned_total{task_name="on-transaction-imported"} 1
polkadot_tasks_spawned_total{task_name="overseer"} 1
polkadot_tasks_spawned_total{task_name="polkadot-runtime-api-request"} 22
polkadot_tasks_spawned_total{task_name="pov-receiver"} 1
polkadot_tasks_spawned_total{task_name="prometheus-endpoint"} 1
polkadot_tasks_spawned_total{task_name="pvf-validation-host"} 1
polkadot_tasks_spawned_total{task_name="runtime-api-subsystem"} 1
polkadot_tasks_spawned_total{task_name="state_request_handler"} 1
polkadot_tasks_spawned_total{task_name="statement-distribution-subsystem"} 1
polkadot_tasks_spawned_total{task_name="telemetry-periodic-send"} 1
polkadot_tasks_spawned_total{task_name="transaction-pool-task-0"} 1
polkadot_tasks_spawned_total{task_name="transaction-pool-task-1"} 1
polkadot_tasks_spawned_total{task_name="txpool-background"} 1
polkadot_tasks_spawned_total{task_name="txpool-notifications"} 1
polkadot_tasks_spawned_total{task_name="warp_sync_request_handler"} 1
# HELP polkadot_tokio_threads_alive Number of threads alive right now
# TYPE polkadot_tokio_threads_alive gauge
polkadot_tokio_threads_alive 39
# HELP polkadot_tokio_threads_total Total number of threads created
# TYPE polkadot_tokio_threads_total counter
polkadot_tokio_threads_total 43
# HELP polkadot_unbounded_channel_len Items in each mpsc::unbounded instance
# TYPE polkadot_unbounded_channel_len counter
polkadot_unbounded_channel_len{action="received",entity="mpsc_background_tasks"} 10787
polkadot_unbounded_channel_len{action="received",entity="mpsc_grandpa_neighbor_packet_worker"} 1
polkadot_unbounded_channel_len{action="received",entity="mpsc_network_worker"} 5407
polkadot_unbounded_channel_len{action="received",entity="mpsc_peerset_messages"} 17
polkadot_unbounded_channel_len{action="send",entity="mpsc_grandpa_neighbor_packet_worker"} 1
polkadot_unbounded_channel_len{action="send",entity="mpsc_network_worker"} 5407
polkadot_unbounded_channel_len{action="send",entity="mpsc_peerset_messages"} 17
```