# Open Source `Category` README Requirements

This document provides the details on the open source category README requirements, including the markdown snippet that should be pasted into the top of a given `README.md` file.

## Category Headers

Every public repository in the `newrelic` and `newrelic-experimental` GitHub organizations must leverage one of the following categories.

- New Relic Experimental
- Community Project
- New Relic One Catalog Project
- Example Code
- Product Delivered in Open Source
- Archived

See the category descriptions, header images, and code snippets below.

## Category: [New Relic Experimental](#new-relic-experimental)

[![New Relic Experimental header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Experimental.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#new-relic-experimental)

### Category Description

This is code that solves an interesting problem but there is no intent to assign an active maintainer.  The code may be developed in the open for the purpose of rapid feedback on a new feature or function.

Projects in New Relic Experimental may *graduate* into the https://github.com/newrelic organization under one of the other categories or be archived.

### Category Requirements

- Must contain the code snippet below at the top of the repository's README file
- Publicly available in the [New Relic Experimental](https://github.com/newrelic-experimental) org
- Issues are optional at the project owner's discertion
- Project follows New Relic's open source licensing requirements
- New Relic Contributor Licensing agreement is implemented and followed
- Repository is monitored for licensing and security compliance


### Code snippet

**Required:** Copy and paste the following into the **top** of your project's README.

```markdown
[![New Relic Experimental header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Experimental.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#new-relic-experimental)
```

## Category: [Community Project](#community-project)

[![Community Project header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Community_Project.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#community-project)

### Category Description

This is code that is developed in the open with input from the community through issues and PRs. There must be an active maintainer team that complies with internal New Relic policy on maintainer expectations. There will be a support Topic in the [New Relic Explorers Hub](https://discuss.newrelic.com) and documentation should be reviewed by the New Relic documentation team.

### Category Requirements

- Must contain the code snippet below at the top of the repository's README file
- has active maintainer / maintainers, including at least one Relic
- a support Topic in the [New Relic Explorers Hub](https://discuss.newrelic.com)
- Issues and PR’s managed in GitHub
- Documentation reviewed by the New Relic documentation team,
- Linted code,
- An automated release pipeline,
- and having successfully navigated any other steps of the internal New Relic Open Source process


### Code snippet

**Required:** Copy and paste the following into the **top** of your project's README.

```markdown
[![Community Project header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Community_Project.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#community-project)
```

## Category: [New Relic One Catalog Project](#nr1-catalog)

[![New Relic One Catalog Project header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/New_Relic_One_Catalog_Project.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#nr1-catalog)

### Category Description

This is code that will be included in the `New Relic One Catalog`.  It must meet certain criteria which include and supercede the requirements for a `Community Project` to qualify for this category. Among them is that the maintainer team will be expected to maintain a public roadmap for the project.

### Category Requirements

All the requirements of a `Community Project` as well as
- The empty state of the application workflow that guides users through the setup of configuration data that is stored in NerdStorage
- Architectural review (including UX),
- Product management review,
- (as needed) Security review,
- and the project must also maintain a public roadmap (recommended via a GitHub project in the repo).

### Code snippet

**Required:** Copy and paste the following into the **top** of your project's README.

```markdown
[![New Relic One Catalog Project header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/New_Relic_One_Catalog_Project.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#nr1-catalog)
```

## Category: [Example Code](#example-code)

[![Example Code header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Example_Code.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#example-code)

### Category Description

This is code that demonstrates how to do something on the New Relic One platform and is attached to a piece of published content (a blog post, video, etc.). It has a complete description of its usage in the README and any other relevant docs. **There is no long-term maintainer for this code** (though there is an author who can be addressed with future updates / needs as platform features change). There will be no [New Relic Explorers Hub](https://discuss.newrelic.com) Topic for support.

### Category Requirements

- Must contain the code snippet below at the top of the repository's README file
- Sample code, demonstrating effective best-practices for a given language (normally attached to a piece of public communication or marketing material ex: Blog post)
- (optional) Issues are available at the project author's discretion
- Reviewed README/docs accompany the code
- Project follows New Relic's open source licensing requirements
- New Relic Contributor Licensing agreement is implemented and followed
- Repository is monitored for licensing and security compliance


### Code snippet

**Required:** Copy and paste the following into the **top** of your project's README.

```markdown
[![Example Code header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Example_Code.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#example-code)
```

## Category: [Product delivered in Open Source](#product-oss)

[![Product delivered in Open Source header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Product_Delivered_in_Open_Source.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#product-oss)

### Category Description

This is code that is developed and maintained by New Relic engineering teams (often but not always) in a private code repository but is delivered via public GitHub.

### Category Requirements

- Must contain the code snippet below at the top of the repository's README file
- README must direct users to the appropriate Support path/channel
- Project follows New Relic's open source licensing requirements
- If the project accepts PR's, the New Relic Contributor Licensing agreement must be implemented and followed
- Repository is monitored for licensing and security compliance


### Code snippet

**Required:** Copy and paste the following into the **top** of your project's README.

```markdown
[![Product delivered in Open Source header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Product_Delivered_in_Open_Source.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#product-oss)
```

## Category: [Archived](#archived)

[![Archived header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Archived.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#archived)

### Category Description

The code is read-only. There is no maintainer team nor support.

### Category Requirements

- Must contain the code snippet below at the top of the repository's README file
- Previous references to Support should be modified or removed from the README
- Project is read-only and available for `cloning` only
- Project follows New Relic's open source licensing requirements

### Code snippet

**Required:** Copy and paste the following into the **top** of your project's README.

```markdown
[![Archived header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Archived.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#archived)
```
