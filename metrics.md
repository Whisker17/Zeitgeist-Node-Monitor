# Metrics

Zeitgeist can currently support a large amount of data information monitoring. The current template selects some of the more commonly used ones. If you need to customize it yourself, you can refer to the following metrics to modify.



- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** Number of external addresses published when authority discovery last published addresses.

  - **Type：** gauge

- **polkadot_authority_discovery_authority_address_requests_pending**

  - **Info：** Number of pending authority address requests. 

  - **Type：** gauge

- **polkadot_authority_discovery_authority_addresses_requested_total**

  - **Info：** Number of times authority discovery has requested external addresses of a single authority.

  - **Type：** counter

- **polkadot_authority_discovery_dht_event_received**

  - **Info：** Number of dht events received by authority discovery.

  - **Type：** counter

- **polkadot_authority_discovery_handle_value_found_event_failure**

  - **Info：** Number of times handling a dht value found event failed.

  - **Type：** counter

- **polkadot_authority_discovery_known_authorities_count**

  - **Info：** Number of authorities known by authority discovery.

  - **Type：** gauge

- **polkadot_authority_discovery_times_published_total**

  - **Info：** Number of times authority discovery has published external addresses.

  - **Type：** counter

- **polkadot_block_height**

  - **Info：** Block height info of the chain

  - **Type：** gauge

- **polkadot_block_verification_and_import_time_bucket**

  - **Info：** Time taken to verify and import blocks

  - **Type：** histogram

- **polkadot_block_verification_and_import_time_sum**

  - **Info：** 

  - **Type：** 

- **polkadot_block_verification_and_import_time_count**

  - **Info：** 

  - **Type：** 

- **polkadot_build_info**

  - **Info：** A metric with a constant '1' value labeled by name, version

  - **Type：** gauge

- **polkadot_database_cache_bytes**

  - **Info：** RocksDB cache size in bytes

  - **Type：** gauge

- **polkadot_finality_grandpa_precommits_total**

  - **Info：** Total number of GRANDPA precommits cast locally.

  - **Type：** counter

- **polkadot_finality_grandpa_prevotes_total**

  - **Info：** Total number of GRANDPA prevotes cast locally.

  - **Type：** counter

- **polkadot_finality_grandpa_round**

  - **Info：** Highest completed GRANDPA round.

  - **Type：** gauge

- **polkadot_finality_grandpa_until_imported_waiting_messages_number**

  - **Info：** Number of finality grandpa messages waiting within the until imported queue.

  - **Type：** gauge

- **polkadot_import_queue_blocks_submitted**

  - **Info：** Number of blocks submitted to the import queue.

  - **Type：** counter

- **polkadot_import_queue_justifications_submitted**

  - **Info：** Number of justifications submitted to the import queue.

  - **Type：** counter

- **polkadot_issued_light_requests**

  - **Info：** Number of light client requests that our node has issued.

  - **Type：** counter

- **polkadot_justification_import_time_bucket**

  - **Info：** Time taken to import justifications

  - **Type：** histogram

- **polkadot_justification_import_time_sum**

  - **Info：** 

  - **Type：** 

- **polkadot_justification_import_time_count**

  - **Info：** 

  - **Type：** 

- **polkadot_network_gossip_expired_messages_total**

  - **Info：** Number of expired messages by the gossip service.

  - **Type：** counter

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 

- **polkadot_authority_discovery_amount_external_addresses_last_published**

  - **Info：** 

  - **Type：** 