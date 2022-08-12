# Tech Stack

This the start of my building of a stable tech stack. Some things are in an
untested state. I put those here because I find them desirable but maybe I
haven't used them much or at all.

Those will be noted in *italics*.

## Linting and Style

Currently using Eslint, Prettier, Husky and lint-staged, but wanna change the
way I use Eslint by using Lynt, which provides a preconfigured Eslint with all
style rules disabled.


- [Eslint repo](https://github.com/eslint/eslint)
- [Eslint site](https://eslint.org/)
  **Since 2016**

> Find and fix problems in your JavaScript code.

- [*Lynt*](https://github.com/saadq/lynt)

> A zero config JavaScript linter with support for Typescript, Flow, and React.
> Uses Eslint under the hood, but no start-up configuration is required.

> Lynt has two main philosophies:

> Zero configuration by default. Out of the box, Lynt is a working linter and
> does not need any configuration. However, if you would like to add or remove
> rules from the default Lynt config, you have the option to do so.

> No style rules. Lynt is completely unopinionated when it comes to code style.
> It doesn't care whether or not you use semicolons, tabs or spaces, trailing
> commas, etc. Lynt only handles the error checking side of things and it leaves
> code style up to better-suited tools like Prettier.

- [Prettier](https://github.com/prettier/prettier)
  **Since 2019**

> Prettier is an opinionated code formatter.

- [Husky](https://github.com/typicode/husky)
  **Since 2020**

> Git hooks made easy.

- [lint-staged](https://github.com/okonet/lint-staged)
  **Since 2020**

> Run linters against staged git files and don't let shit slip into your code
> base.


## Libraries

- [*ts-belt*](https://mobily.github.io/ts-belt/docs/)

- [Ramda](https://ramdajs.com/)

> A library designed specifically for a functional programming style, one that
> makes it easy to create functional pipelines, one that never mutates user
> data.

## Backend

### Database

- [Knex.js](https://knexjs.org/)
  **Since 2016**

> Knex.js (pronounced /kəˈnɛks/) is a "batteries included" SQL query builder for
> PostgreSQL, CockroachDB, MSSQL, MySQL, MariaDB, SQLite3, Oracle, and Amazon
> Redshift designed to be flexible, portable, and fun to use. It features both
> traditional node style callbacks as well as a promise interface for cleaner
> async flow control, a stream interface, full-featured query and schema
> builders, transaction support (with savepoints), connection pooling and
> standardized responses between different query clients and dialects.

- [*MassiveJs*](https://massivejs.org/)

> Massive is a data mapper for Node.js that goes all in on PostgreSQL and
> embraces the power and flexibility of SQL and the relational model. With
> minimal abstractions for the interfaces and tools you already use, its goal
> is to do just enough to make working with your data and your database as easy
> and intuitive as possible, then get out of your way.

> Massive is not an object-relational mapper (ORM)! It doesn't use models, it
> doesn't track state, and it doesn't box you into working and thinking in terms
> of individual entities, barely scratching the surface of what PostgreSQL can
> do. Instead, Massive analyzes and builds an API for the data model expressed
> in your database's tables, views, and functions, simplifying routine SQL
> generation without hiding SQL itself so your applications can use Postgres to
> the fullest possible extent.


## Frontend

- [*Choo*](https://www.choo.io/)

> A 4kb framework for creating sturdy frontend applications.

- [*Mithril*](https://mithril.js.org/)

> Mithril is a modern client-side JavaScript framework for building Single Page
> Applications. It's small (< 10kb gzip), fast and provides routing and XHR
> utilities out of the box.

- [*Riot.js*](https://riot.js.org/)

> Simple and elegant component-based UI library.

**In 2015 I concluded that Riot.js and Mithril where better than React, but
never tried them**

- [*hyperHtml*](https://viperhtml.js.org/)
  **Found on 2019**

> Created to simplify DOM performance best practices, hyperHTML is 100%
> ECMAScript compliant and it weights about 5Kb, featuring:

> - best in class repeated renders and updates performance
> - declarative and reactive UI via standard template literals
> - an ideal solution via Webpack bundles
> - auto sanitized text content when needed
> - partial outputs between nodes
> - asynchronous content, renders on demand

> Framework agnostic, hyperHTML can be used to render any view, including Custom
> Elements and Web Components.

- [*Svelte*](https://svelte.dev/)
  **Found after hyperHtml, on 2019 too**
> Svelte is a radical new approach to building user interfaces. Whereas
> traditional frameworks like React and Vue do the bulk of their work in the
> browser, Svelte shifts that work into a compile step that happens when you
> build your app.

> Instead of using techniques like virtual DOM diffing, Svelte writes code that
> surgically updates the DOM when the state of your app changes.

## Testing

- [Frisby.js](https://docs.frisbyjs.com/)

> The Easiest REST API Testing Framework Out There.


## Language

- [*ReScript*](https://rescript-lang.org/)
