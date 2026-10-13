Wiki Information

- Name: Witky Sample Wiki
- Purpose: Test a GitHub-backed wiki reader and dynamically generated repository index.
- Primary Subject: Introductory Mathematics
- Content Format: Markdown
- Default Branch: main
- Main Entry Point: "Home" (Home.md)

Organization

The "PROJECTS/" directory is used in this sample to group subject projects. It is an illustrative repository convention, not a requirement that every wiki must use this exact directory name.

The Mathematics project contains two sections:

- "Numbers" (PROJECTS/Mathematics/Numbers/Home.md)
- "Sets" (PROJECTS/Mathematics/Sets/Home.md)

Dynamic Discovery

The application should obtain the repository tree from GitHub, construct its index from the discovered paths, and fetch article content when needed. The displayed index must not depend on a hardcoded list of articles.

Limitations

This sample focuses on introductory definitions and properties. It does not attempt to cover all of mathematics, and its articles may be expanded as the reader application develops.
