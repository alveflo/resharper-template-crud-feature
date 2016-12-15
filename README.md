# Resharper CRUD feature template
Generates a CRUD feature with NHibernate and Appeaser.

### Folder structure
Creating a feature called `Document` generates:
```
Document
- Commands
- - CreateDocument.cs
- - DeleteDocument.cs
- - UpdateDocument.cs
- Queries
- - GetDocument.cs
- - GetDocumentList.cs
- DocumentController.cs
```

For further information, check out the examples folder.
