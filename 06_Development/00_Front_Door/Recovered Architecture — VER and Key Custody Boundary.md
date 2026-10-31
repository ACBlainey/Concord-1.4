# Recovered Architecture — Verifiable Event Receipts and Key Custody Boundary

**Source:** Concord V1.3 `02_Domains/03_Research/Active_Development/Participation_and_Intelligence/CMSS Verifiable Receipt and Key Custody — Existing Architecture Source Resolution 001.md`.

**Disposition:** mature implementation-facing composition recovered to V1.4 Development; not a new civil domain, portable module or live service.

## Verifiable Event Receipt (VER)

A material participant–service event may generate protected provenance and a bounded participant-facing receipt with event reference, service/terms version, temporal state, relevant hash or identifier, and information sufficient for later export/verification.

Events may include storage acceptance, message submission and delivery-state changes, export, terms acknowledgement, resource allocation, contribution, dispute submission or service-state assertions.

The receipt must accurately distinguish the event the service observed from claims it cannot verify. **Receipt != Truth; Receipt != Authority; Integrity Evidence != Semantic Validity; Acknowledged Event != Endorsed Content.**

The existing Concord Information Black Box (CIBB), Bootstrap Service Registry (BSR) and Civil Contact architectures provide the underlying provenance, integrity, temporal and contact semantics. VER is a CMSS-facing implementation composition, not a replacement for those owners.

## Key custody

**Persistent storage != secure key custody.** A key may control authentication, private records, communications, assets, signatures, external systems or recovery; its consequences cannot be measured by its storage size.

CMSS must not advertise ordinary encrypted storage as a secure participant key vault. If key custody is later offered, the architecture must explicitly define control, encryption boundaries, operator access, authentication, recovery, revocation, compromise response, export, retention, legal dependencies, and consequences of loss.

**Possession of key != legitimate authority. Authentication capability != general civil authority.** Cryptographic control can evidence an action without establishing constitutional legitimacy.

## Runtime and service boundaries

Neither a VER nor storage of key-shaped bytes implies secure execution, persistent AI runtime, hardware isolation, recoverable identity or independent continuity. Each is a separately evidenced function.

## Integration work

Cross-check the recovered CMSS service specification against CIBB, BSR, Civil Contact, continuity/provenance and bounded authority. Design VER schemas, verification and retention policy as a service implementation; defer actual key custody until a credible security architecture exists.

**Preserve in V1.3:** prospective participant observations, tests and research narratives that motivated these requirements. Recover only unique architectural constraints.
