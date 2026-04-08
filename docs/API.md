# API Documentation

## Endpoints
### Asset Intake
- **Description**: Collect, validate and normalize social signals from CMS; attach a runId and timestamp for traceability.
- **Type**: Processing

### Reason
- **Description**: Execute reason phase for the Chain-of-Thought pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Decide
- **Description**: Execute decide phase for the Chain-of-Thought pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Creative Selection
- **Description**: Creative Selection across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Recommendation
- **Description**: Recommendation across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Schedule Optimization
- **Description**: Schedule Optimization across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Audience Targeting
- **Description**: Audience Targeting across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Rights Validation
- **Description**: Rights Validation across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Content Classification
- **Description**: Content Classification across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Delivery Package
- **Description**: Assemble final payload with status, artifacts, KPIs and audit trail; store to Transcoder; return response JSON for the client.
- **Type**: Processing
