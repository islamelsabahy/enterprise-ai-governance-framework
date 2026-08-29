# RAG Access Control

Recommended sequence:

```text
User Identity
→ Authorization
→ Permitted Sources
→ Retrieval
→ Filtering
→ Generation
```

Access filtering must occur before content is exposed to the model or user.

Avoid using post-generation redaction as the primary access-control mechanism.
