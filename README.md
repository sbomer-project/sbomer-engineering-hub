# sbomer-engineering-hub
This repository serves as a home base for issues and documentation related to SBOMer project.

Documentation available at: https://sbomer-project.github.io/sbomer-engineering-hub/

---

## Local development
To run the documentation locally, you can use the following command:

```bash
npx antora antora-playbook.yml
```
to build and then
```bash
npx http-server build/site -c-1
```
to serve the documentation on `http://localhost:8080`.