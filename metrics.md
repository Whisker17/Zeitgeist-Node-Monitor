# Metrics

Zeitgeist can currently support a large amount of data information monitoring. The current template selects some of the more commonly used ones. If you need to customize it yourself, you can refer to the following metrics to modify.

> Tips: subcommand means that the function can also view more information through subcommands.

<!-- vscode-markdown-toc -->

- 1. [Info](#Info)
- 2. [Interactive Information](#InteractiveInformation)
- 3. [Storage](#Storage)
- 4. [Performance](#Performance)
- 5. [Errors](#Errors)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

## 1. <a name='Info'></a>Info

This part of the function contains some basic information of the local node.

- **polkadot_block_height**

  - **Info:** Block height info of the chain

  - **Type:** gauge

- **polkadot_build_info**

  - **Info:** A metric with a constant '1' value labeled by name, version

  - **Type:** gauge

- **polkadot_node_roles**

  - **Info:** The roles the node is running as

  - **Type:** gauge

- **polkadot_ready_transactions_number**

  - **Info:** Number of transactions in the ready queue

  - **Type:** gauge

- **polkadot_sub_libp2p_is_major_syncing**

  - **Info:** Whether the node is performing a major sync or not.

  - **Type:** gauge

- **polkadot_sub_libp2p_network_bytes_total**

  - **Info:** Total bandwidth usage

  - **Type:** counter

## 2. <a name='InteractiveInformation'></a>Interactive Information

The functions in Interactive Information can be used to query the connection between nodes and the network and some consensus conditions.

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info:** Number of external addresses published when authority discovery last published addresses.

  - **Type:** gauge

- **polkadot_authority_discovery_authority_address_requests_pending**

  - **Info:** Number of pending authority address requests.

  - **Type:** gauge

- **polkadot_authority_discovery_authority_addresses_requested_total**

  - **Info:** Number of times authority discovery has requested external addresses of a single authority.

  - **Type:** counter

- **polkadot_authority_discovery_dht_event_received**

  - **Info:** Number of dht events received by authority discovery.

  - **Type:** counter

- **polkadot_authority_discovery_handle_value_found_event_failure**

  - **Info:** Number of times handling a dht value found event failed.

  - **Type:** counter

- **polkadot_authority_discovery_known_authorities_count**

  - **Info:** Number of authorities known by authority discovery.

  - **Type:** gauge

- **polkadot_authority_discovery_times_published_total**

  - **Info:** Number of times authority discovery has published external addresses.

  - **Type:** counter

- **polkadot_block_verification_and_import_time_bucket**

  - **Info:** Time taken to verify and import blocks

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_block_verification_and_import_time_sum**

    - **polkadot_block_verification_and_import_time_count**

- **polkadot_finality_grandpa_precommits_total**

  - **Info:** Total number of GRANDPA precommits cast locally.

  - **Type:** counter

- **polkadot_finality_grandpa_prevotes_total**

  - **Info:** Total number of GRANDPA prevotes cast locally.

  - **Type:** counter

- **polkadot_finality_grandpa_round**

  - **Info:** Highest completed GRANDPA round.

  - **Type:** gauge

- **polkadot_finality_grandpa_until_imported_waiting_messages_number**

  - **Info:** Number of finality grandpa messages waiting within the until imported queue.

  - **Type:** gauge

- **polkadot_import_queue_blocks_submitted**

  - **Info:** Number of blocks submitted to the import queue.

  - **Type:** counter

- **polkadot_import_queue_justifications_submitted**

  - **Info:** Number of justifications submitted to the import queue.

  - **Type:** counter

- **polkadot_issued_light_requests**

  - **Info:** Number of light client requests that our node has issued.

  - **Type:** counter

- **polkadot_justification_import_time_bucket**

  - **Info:** Time taken to import justifications

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_justification_import_time_sum**

    - **polkadot_justification_import_time_count**

- **polkadot_network_gossip_expired_messages_total**

  - **Info:** Number of expired messages by the gossip service.

  - **Type:** counter

- **polkadot_network_gossip_registered_messages_total**

  - **Info:** Number of registered messages by the gossip service.

  - **Type:** counter

- **polkadot_parachain_activated_heads_total**

  - **Info:** Number of activated heads.

  - **Type:** counter

- **polkadot_parachain_approval_checking_finality_lag**

  - **Info:** How far behind the head of the chain the Approval Checking protocol wants to vote

  - **Type:** gauge

- **polkadot_parachain_approvals_blockapproval_time_ticks_bucket**

  - **Info:** Number of ticks (500ms) to approve blocks.

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_approvals_blockapproval_time_ticks_sum**

    - **polkadot_parachain_approvals_blockapproval_time_ticks_count**

- **polkadot_parachain_approvals_candidate_approval_time_ticks_bucket**

  - **Info:** Number of ticks (500ms) to approve candidates.

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_approvals_candidate_approval_time_ticks_sum**

    - **polkadot_parachain_approvals_candidate_approval_time_ticks_count**

- **polkadot_parachain_approvals_imported_total**

  - **Info:** Number of valid approvals imported locally or from other peers.

  - **Type:** counter

- **polkadot_parachain_approvals_no_shows_total**

  - **Info:** Number of assignments which became no-shows in the approval voting subsystem

  - **Type:** counter

- **polkadot_parachain_approvals_wakeups_total**

  - **Info:** Number of times we woke up to process a candidate in the approval voting subsystem

  - **Type:** counter

- **polkadot_parachain_assignments_imported_total**

  - **Info:** Number of valid assignments imported locally or from other peers.

  - **Type:** counter

- **polkadot_parachain_assignments_produced_bucket**

  - **Info:** Assignments and tranches produced by the approval voting subsystem

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_assignments_produced_sum**

    - **polkadot_parachain_assignments_produced_count**

- **polkadot_parachain_chain_api_requests_total**

  - **Info:** Number of Chain API requests served.

  - **Type:** counter

- **polkadot_parachain_collation_advertisements_made_total**

  - **Info:** A number of collation advertisements sent to validators.

  - **Type:** counter

- **polkadot_parachain_collations_sent_requested_total**

  - **Info:** A number of collations requested to be sent to validators.

  - **Type:** counter

- **polkadot_parachain_collations_sent_total**

  - **Info:** A number of collations sent to validators.

  - **Type:** counter

- **polkadot_number_leaves**

  - **Info:** Number of known chain leaves (aka forks)

  - **Type:** gauge

- **polkadot_parachain_bitfields_signed_total**

  - **Info:** Number of bitfields signed.

  - **Type:** counter

- **polkadot_parachain_candidate_backing_candidates_seconded_total**

  - **Info:** Number of candidates seconded.

  - **Type:** counter

- **polkadot_parachain_candidate_backing_signed_statements_total**

  - **Info:** Number of statements signed.

  - **Type:** counter

- **polkadot_parachain_collations_generated_total**

  - **Info:** Number of collations generated.

  - **Type:** counter

- **polkadot_parachain_deactivated_heads_total**

  - **Info:** Number of deactivated heads.

  - **Type:** counter

- **polkadot_parachain_dispute_distribution_received_requests**

  - **Info:** Total number of received dispute requests.

  - **Type:** counter

- **polkadot_parachain_disputes_finality_lag**

  - **Info:** How far behind the head of the chain the Disputes protocol wants to vote

  - **Type:** gauge

- **polkadot_parachain_fetch_retries_total**

  - **Info:** Number of times we did not succeed in fetching a chunk and needed to try more backers.

  - **Type:** counter

- **polkadot_parachain_gossipped_own_availabilty_bitfields_total**

  - **Info:** Number of own availability bitfields sent to other peers.

  - **Type:** counter

- **polkadot_parachain_imported_candidates_total**

  - **Info:** Number of candidates imported by the approval voting subsystem

  - **Type:** counter

- **polkadot_parachain_messages_relayed_total**

  - **Info:** Number of messages relayed by Overseer.

  - **Type:** counter

- **polkadot_parachain_notification_bytes_sent_total**

  - **Info:** The number of bytes sent on a parachain notification protocol

  - **Type:** counter

- **polkadot_parachain_notifications_sent_total**

  - **Info:** The number of notifications sent on a parachain protocol

  - **Type:** counter

- **polkadot_parachain_overseer_signals_received**

  - **Info:** Number of signals received by subsystems from overseer

  - **Type:** gauge

- **polkadot_parachain_overseer_signals_sent**

  - **Info:** Number of signals sent by overseer to subsystems

  - **Type:** gauge

- **polkadot_parachain_received_availability_chunks_total**

  - **Info:** Number of availability chunks received.

  - **Type:** counter

- **polkadot_parachain_received_availabilty_bitfields_total**

  - **Info:** Number of valid availability bitfields received from other peers.

  - **Type:** counter

- **polkadot_parachain_runtime_api_requests_total**

  - **Info:** Number of Runtime API requests served.

  - **Type:** counter

- **polkadot_parachain_statement_distribution_sent_requests_total**

  - **Info:** Number of large statement fetching requests sent.

  - **Type:** counter

- **polkadot_parachain_statements_distributed_total**

  - **Info:** Number of candidate validity statements distributed to other peers.

  - **Type:** counter

- **polkadot_sub_libp2p_connections_closed_total**

  - **Info:** Total number of connections closed, by direction and reason

  - **Type:** counter

- **polkadot_sub_libp2p_connections_opened_total**

  - **Info:** Total number of connections opened by direction

  - **Type:** counter

- **polkadot_sub_libp2p_distinct_peers_connections_closed_total**

  - **Info:** Total number of connections closed with distinct peers

  - **Type:** counter

- **polkadot_sub_libp2p_distinct_peers_connections_opened_total**

  - **Info:** Total number of connections opened with distinct peers

  - **Type:** counter

- **polkadot_sub_libp2p_incoming_connections_total**

  - **Info:** Total number of incoming connections on the listening sockets

  - **Type:** counter

- **polkadot_sub_libp2p_kademlia_query_duration_bucket**

  - **Info:** Duration of Kademlia queries per query type

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_sub_libp2p_kademlia_query_duration_sum**

    - **polkadot_sub_libp2p_kademlia_query_duration_count**

- **polkadot_sub_libp2p_kademlia_random_queries_total**

  - **Info:** Number of random Kademlia queries started

  - **Type:** counter

- **polkadot_sub_libp2p_kademlia_records_count**

  - **Info:** Number of records in the Kademlia records store

  - **Type:** gauge

- **polkadot_sub_libp2p_kbuckets_num_nodes**

  - **Info:** Number of nodes per kbucket per Kademlia instance

  - **Type:** gauge

- **polkadot_sub_libp2p_listeners_local_addresses**

  - **Info:** Number of local addresses we're listening on

  - **Type:** gauge

- **polkadot_sub_libp2p_out_events_events_total**

  - **Info:** Number of broadcast network events that have been sent or received across all channels

  - **Type:** counter

- **polkadot_sub_libp2p_out_events_num_channels**

  - **Info:** Number of internal active channels that broadcast network events

  - **Type:** gauge

- **polkadot_sub_libp2p_peers_count**

  - **Info:** Number of connected peers

  - **Type:** gauge

- **polkadot_sub_libp2p_peerset_num_discovered**

  - **Info:** Number of nodes stored in the peerset manager

  - **Type:** gauge

- **polkadot_sub_libp2p_peerset_num_requested**

  - **Info:** Number of nodes that the peerset manager wants us to be connected to

  - **Type:** gauge

- **polkadot_sub_libp2p_pending_connections**

  - **Info:** Number of connections in the process of being established

  - **Type:** gauge

- **polkadot_sub_txpool_block_transactions_pruned**

  - **Info:** Total number of transactions that was requested to be pruned by block events

  - **Type:** counter

- **polkadot_sub_txpool_block_transactions_resubmitted**

  - **Info:** Total number of transactions that was requested to be resubmitted by block events

  - **Type:** counter

- **polkadot_sub_txpool_submitted_transactions**

  - **Info:** Total number of transactions submitted

  - **Type:** counter

- **polkadot_sub_txpool_validations_finished**

  - **Info:** Total number of transactions that finished validation

  - **Type:** counter

- **polkadot_sub_txpool_validations_invalid**

  - **Info:** Total number of transactions that were removed from the pool as invalid

  - **Type:** counter

- **polkadot_sub_txpool_validations_scheduled**

  - **Info:** Total number of transactions scheduled for validation

  - **Type:** counter

- **polkadot_sync_extra_justifications**

  - **Info:** Number of extra justifications requests

  - **Type:** gauge

- **polkadot_sync_fork_targets**

  - **Info:** Number of fork sync targets

  - **Type:** gauge

- **polkadot_sync_peers**

  - **Info:** Number of peers we sync with

  - **Type:** gauge

- **polkadot_sync_propagated_transactions**

  - **Info:** Number of transactions propagated to at least one peer

  - **Type:** counter

- **polkadot_sync_queued_blocks**

  - **Info:** Number of blocks in import queue

  - **Type:** gauge

## 3. <a name='Storage'></a>Storage

The functions in Storage support querying node storage related information.

- **polkadot_database_cache_bytes**

  - **Info:** RocksDB cache size in bytes

  - **Type:** gauge

- **polkadot_state_cache_bytes**

  - **Info:** State cache size in bytes

  - **Type:** gauge

- **polkadot_state_db_cache_bytes**

  - **Info:** State DB cache in bytes

  - **Type:** gauge

- **polkadot_sub_libp2p_kademlia_records_sizes_total**

  - **Info:** Total size of all the records in the Kademlia records store

  - **Type:** gauge

## 4. <a name='Performance'></a>Performance

Performance related functions can show the performance status of the node, including function call time, subsystem interaction status and task status.

- **polkadot_parachain_av_store_block_activated_bucket**

  - **Info:** Time spent within `av_store::process_block_activated`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_av_store_block_activated_sum**

    - **polkadot_parachain_av_store_block_activated_count**

- **polkadot_parachain_av_store_get_chunk_bucket**

  - **Info:** Time spent fetching requested chunks.

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_av_store_get_chunk_sum**

    - **polkadot_parachain_av_store_get_chunk_count**

- **polkadot_parachain_av_store_process_block_finalized_bucket**

  - **Info:** Time spent within `av_store::process_block_finalized`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_av_store_process_block_finalized_sum**

    - **polkadot_parachain_av_store_process_block_finalized_count**

- **polkadot_parachain_av_store_process_message_bucket**

  - **Info:** Time spent within `av_store::process_message`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_av_store_process_message_sum**

    - **polkadot_parachain_av_store_process_message_count**

- **polkadot_parachain_av_store_pruning_bucket**

  - **Info:** Time spent within `av_store::prune_all`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_av_store_pruning_sum**

    - **polkadot_parachain_av_store_pruning_count**

- **polkadot_parachain_av_store_store_available_data_bucket**

  - **Info:** Time spent within `av_store::store_available_data`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_av_store_store_available_data_sum**

    - **polkadot_parachain_av_store_store_available_data_count**

- **polkadot_parachain_av_store_store_chunk_bucket**

  - **Info:** Time spent within `av_store::store_chunk`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_av_store_store_chunk_sum**

    - **polkadot_parachain_av_store_store_chunk_count**

- **polkadot_parachain_bitfield_distribution_active_leaves_update_bucket**

  - **Info:** Time spent within `bitfield_distribution::active_leaves_update`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_bitfield_distribution_active_leaves_update_sum**

    - **polkadot_parachain_bitfield_distribution_active_leaves_update_count**

- **polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_bucket**

  - **Info:** Time spent within `bitfield_distribution::handle_bitfield_distribution`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_sum**

    - **polkadot_parachain_bitfield_distribution_handle_bitfield_distribution_count**

- **polkadot_parachain_bitfield_distribution_handle_network_msg_bucket**

  - **Info:** Time spent within `bitfield_distribution::handle_network_msg`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_bitfield_distribution_handle_network_msg_sum**

    - **polkadot_parachain_bitfield_distribution_handle_network_msg_count**

- **polkadot_parachain_bitfield_signing_run_bucket**

  - **Info:** Time spent within `bitfield_signing::run`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_bitfield_signing_run_sum**

    - **polkadot_parachain_bitfield_signing_run_count**

- **polkadot_parachain_candidate_backing_get_backed_candidates_bucket**

  - **Info:** Time spent within `candidate_backing::get_backed_candidates`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_candidate_backing_get_backed_candidates_sum**

    - **polkadot_parachain_candidate_backing_get_backed_candidates_count**

- **polkadot_parachain_candidate_backing_process_second_bucket**

  - **Info:** Time spent within `candidate_backing::process_second`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_candidate_backing_process_second_sum**

    - **polkadot_parachain_candidate_backing_process_second_count**

- **polkadot_parachain_candidate_backing_process_statement_bucket**

  - **Info:** Time spent within `candidate_backing::process_statement`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_candidate_backing_process_statement_sum**

    - **polkadot_parachain_candidate_backing_process_statement_count**

- **polkadot_parachain_candidate_validation_validate_candidate_exhaustive_bucket**

  - **Info:** Time spent within `candidate_validation::validate_candidate_exhaustive`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_candidate_validation_validate_candidate_exhaustive_sum**

    - **polkadot_parachain_candidate_validation_validate_candidate_exhaustive_count**

- **polkadot_parachain_candidate_validation_validate_from_chain_state_bucket**

  - **Info:** Time spent within `candidate_validation::validate_from_chain_state`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_candidate_validation_validate_from_chain_state_sum**

    - **polkadot_parachain_candidate_validation_validate_from_chain_state_count**

- **polkadot_parachain_candidate_validation_validate_from_exhaustive_bucket**

  - **Info:** Time spent within `candidate_validation::validate_from_exhaustive`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_candidate_validation_validate_from_exhaustive_sum**

    - **polkadot_parachain_candidate_validation_validate_from_exhaustive_count**

- **polkadot_parachain_chain_api_ancestors_bucket**

  - **Info:** Time spent within `chain_api::ancestors`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_chain_api_ancestors_sum**

    - **polkadot_parachain_chain_api_ancestors_count**

- **polkadot_parachain_chain_api_block_headers_bucket**

  - **Info:** Time spent within `chain_api::block_headers`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_chain_api_block_headers_sum**

    - **polkadot_parachain_chain_api_block_headers_count**

- **polkadot_parachain_chain_api_block_number_bucket**

  - **Info:** Time spent within `chain_api::block_number`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_chain_api_block_number_sum**

    - **polkadot_parachain_chain_api_block_number_count**

- **polkadot_parachain_chain_api_block_weight_bucket**

  - **Info:** Time spent within `chain_api::block_weight`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_chain_api_block_weight_sum**

    - **polkadot_parachain_chain_api_block_weight_count**

- **polkadot_parachain_chain_api_finalized_block_hash_bucket**

  - **Info:** Time spent within `chain_api::finalized_block_hash`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_chain_api_finalized_block_hash_sum**

    - **polkadot_parachain_chain_api_finalized_block_hash_count**

- **polkadot_parachain_chain_api_finalized_block_number_bucket**

  - **Info:** Time spent within `chain_api::finalized_block_number`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_chain_api_finalized_block_number_sum**

    - **polkadot_parachain_chain_api_finalized_block_number_count**

- **polkadot_parachain_collation_generation_new_activations_bucket**

  - **Info:** Time spent within fn `handle_new_activations`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_collation_generation_new_activations_sum**

    - **polkadot_parachain_collation_generation_new_activations_count**

- **polkadot_parachain_collation_generation_per_availability_core_bucket**

  - **Info:** Time spent handling a particular availability core for a relay parent in fn `handle_new_activations`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_collation_generation_per_availability_core_sum**

    - **polkadot_parachain_collation_generation_per_availability_core_count**

- **polkadot_parachain_collation_generation_per_relay_parent_bucket**

  - **Info:** Time spent handling a particular relay parent within fn `handle_new_activations`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_collation_generation_per_relay_parent_sum**

    - **polkadot_parachain_collation_generation_per_relay_parent_count**

- **polkadot_parachain_collator_protocol_collator_process_msg_bucket**

  - **Info:** Time spent within `collator_protocol_collator::process_msg`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_collator_protocol_collator_process_msg_sum**

    - **polkadot_parachain_collator_protocol_collator_process_msg_count**

- **polkadot_parachain_provisioner_provisionable_data_bucket**

  - **Info:** Time spent within `provisioner::provisionable_data`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_provisioner_provisionable_data_sum**

    - **polkadot_parachain_provisioner_provisionable_data_count**

- **polkadot_parachain_provisioner_request_inherent_data_bucket**

  - **Info:** Time spent within `provisioner::request_inherent_data`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_provisioner_request_inherent_data_sum**

    - **polkadot_parachain_provisioner_request_inherent_data_count**

- **polkadot_parachain_runtime_api_make_runtime_api_request_bucket**

  - **Info:** Time spent within `runtime_api::make_runtime_api_request`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_runtime_api_make_runtime_api_request_sum**

    - **polkadot_parachain_runtime_api_make_runtime_api_request_count**

- **polkadot_parachain_statement_distribution_active_leaves_update_bucket**

  - **Info:** Time spent within `statement_distribution::active_leaves_update`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_statement_distribution_active_leaves_update_sum**

    - **polkadot_parachain_statement_distribution_active_leaves_update_count**

- **polkadot_parachain_statement_distribution_network_bridge_update_v1_bucket**

  - **Info:** Time spent within `statement_distribution::network_bridge_update_v1`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_statement_distribution_network_bridge_update_v1_sum**

    - **polkadot_parachain_statement_distribution_network_bridge_update_v1_count**

- **polkadot_parachain_statement_distribution_share_bucket**

  - **Info:** Time spent within `statement_distribution::share`

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_statement_distribution_share_sum**

    - **polkadot_parachain_statement_distribution_share_count**

- **polkadot_parachain_subsystem_bounded_received**

  - **Info:** Number of elements received by subsystems' bounded queues

  - **Type:** gauge

- **polkadot_parachain_subsystem_bounded_sent**

  - **Info:** Number of elements sent to subsystems' bounded queues

  - **Type:** gauge

- **polkadot_parachain_subsystem_unbounded_received**

  - **Info:** Number of elements received by subsystems' unbounded queues

  - **Type:** gauge

- **polkadot_parachain_subsystem_unbounded_sent**

  - **Info:** Number of elements sent to subsystems' unbounded queues

  - **Type:** gauge

- **polkadot_parachain_time_approval_db_transaction_bucket**

  - **Info:** Time spent writing an approval db transaction.

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_time_approval_db_transaction_sum**

    - **polkadot_parachain_time_approval_db_transaction_count**

- **polkadot_parachain_time_awaiting_approval_voting_bucket**

  - **Info:** Time spent awaiting a reply from the Approval Voting Subsystem.

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_time_awaiting_approval_voting_sum**

    - **polkadot_parachain_time_awaiting_approval_voting_count**

- **polkadot_parachain_time_import_pending_now_known_bucket**

  - **Info:** Time spent on importing pending assignments and approvals.

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_time_import_pending_now_known_sum**

    - **polkadot_parachain_time_import_pending_now_known_count**

- **polkadot_parachain_time_recover_and_approve_bucket**

  - **Info:** Time spent recovering and approving data in approval voting

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_time_recover_and_approve_sum**

    - **polkadot_parachain_time_recover_and_approve_count**

- **polkadot_parachain_time_unify_with_peer_bucket**

  - **Info:** Time spent within fn `unify_with_peer`.

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_parachain_time_unify_with_peer_sum**

    - **polkadot_parachain_time_unify_with_peer_count**

- **polkadot_parachain_unified_with_peer_total**

  - **Info:** Number of times `unify_with_peer` is called.

  - **Type:** counter

- **polkadot_process_start_time_seconds**

  - **Info:** Number of seconds between the UNIX epoch and the moment the process started

  - **Type:** gauge

- **polkadot_tasks_ended_total**

  - **Info:** Total number of tasks for which Future::poll has returned Ready(()) or panicked

  - **Type:** counter

- **polkadot_tasks_polling_duration_bucket**

  - **Info:** Duration in seconds of each invocation of Future::poll

  - **Type:** histogram

  - **Subcommand:**

    - **polkadot_tasks_polling_duration_sum**

    - **polkadot_tasks_polling_duration_count**

- **polkadot_tasks_polling_started_total**

  - **Info:** Total number of times we started invoking Future::poll

  - **Type:** counter

- **polkadot_tasks_spawned_total**

  - **Info:** Total number of tasks that have been spawned on the Service

  - **Type:** counter

- **polkadot_tokio_threads_alive**

  - **Info:** Number of threads alive right now

  - **Type:** gauge

- **polkadot_tokio_threads_total**

  - **Info:** Total number of threads created

  - **Type:** counter

- **polkadot_unbounded_channel_len**

  - **Info:** Items in each mpsc::unbounded instance

  - **Type:** counter

## 5. <a name='Errors'></a>Errors

The functions in Errors can help monitor error messages during node operation.

- **polkadot_sub_libp2p_listeners_errors_total**

  - **Info:** Total number of non-fatal errors reported by a listener

  - **Type:** counter

- **polkadot_sub_libp2p_pending_connections_errors_total**

  - **Info:** Total number of pending connection errors

  - **Type:** counter
