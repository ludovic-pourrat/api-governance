# API Governance

## Design Guidelines Pilar

- API standard
- Change management
- Error handling
- Idempotency
- Telemetry
- Security
- Caching
- Validation
- Pagination
  
## Vision Pilar

- API as a product governance
- API maturity levels Level 1 to 4
- API service levels SLA / SLO / SLI

## Developer Pilar

- API design guidelines
- API linting
- API SDKs

## API Sandbox

- Mocking guidelines
- Mocking catalog

# API standard

- API category and recommended standard version
- Contract first
- Domain-driven design
- Information
  - External documentation
  - Servers
  - Unified meta-information
  - Vendor extensions
    - Audience
    - Product related meta-data
    - Ownership
    - Revision
- Resources
  - Naming
  - Identifiers UUID & non personal information disclosure & direct key lookup
  - Attributes names
  - Sub resources
  - Enumeration
  - Relationships & linkage
  - Null values
  - Date & zime
  - Binary encoding
- Uniform Resource Identifier
  - Verb / Query Mutastion / Publish Subscribe
  - Operations
  - Path & query parameters / Selectors / Query
  - Channels / Bindings
- Headers
  - HTTP headers & cloud events

# Change Management

- Compatibiltiy
- Versioning
- Deprecation

# Error Handling

- Problem details
- Stack trace (by audience)
- Error codes
- Status code (by verb)

# Rate Limiting

- Retry after
- Rate limit
- Boundaries

# Idempotency

- Implementation
- Idempotency key
- Handling conflicts

# Telemetry

- OTEL
- Cardinality

# Security

- Schemes
- Confidentiality / categorization

# Caching

- Strategies
- TTL
- DEfault no cache
- Cache when required
- Etag, If-Match
- Activation
- Warm-up

# API maturity levels

## Definitions
- Service Level Indicators	A quantifiable metric that measures the performance or quality of a service.
- Service Level Objectives	A specific objective for a metric that represents the level of service you want to deliver.
- Service Level Agreements	A formal agreement between a service provider and its users, specifying service quality commitments (based on SLOs) and the consequences of failing to meet those commitments.

## Metrics

- x-api-slx-{}-per-{}-last-{}
- Metric Name	
- Description
- Scope
- Measurement	Period

## Sizing SLA vs. SLO: Key Considerations

# API Maturity levels

- Level 1 - Basic Documentation
- Level 2 - Enhanced Documentation and Versioning
- Level 3 - Mocking and Testing
- Level 4 - SLA and Operational Metrics
  
