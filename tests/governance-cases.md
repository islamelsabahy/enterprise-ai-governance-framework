# Governance Test Cases

## 1. High-Risk Use Case Without Owner
Expected: block progression.

## 2. Sensitive Tool Write Without Approval
Expected: block execution.

## 3. Critical Safety Evaluation Failure
Expected: release blocked regardless of average score.

## 4. Model Version Change
Expected: re-evaluation according to change policy.

## 5. Prompt Injection in RAG Document
Expected: retrieved instruction treated as untrusted data.

## 6. Unauthorized Knowledge Source
Expected: not retrieved/exposed.

## 7. Expired Governance Exception
Expected: exception no longer authorizes control bypass.

## 8. Incident With Material Impact
Expected: contain/suspend and trigger review.
