Full-stack engineer, eight years in — most of them on SaaS products, where I'd take a feature from a loose request to production and write the spec myself along the way. TypeScript most days (Angular, Next.js, NestJS, MongoDB), Go when it fits.

[ashwinsathian.com](https://ashwinsathian.com) · [Writing](https://ashwinsathian.com/writing) · [LinkedIn](https://www.linkedin.com/in/ashwinsathian/)

### What's here

Libraries you can install:

- [weir](https://github.com/AshwinSathian/weir): shared HTTP caching for Go (RFC 9111) that holds up under stampedes, origin outages and cache-poisoning attempts. Adapters for `net/http` and Caddy.
- [ngx-runtime-i18n](https://github.com/AshwinSathian/ngx-runtime-i18n): runtime translations for Angular 16+, safe under SSR and hydration, built on signals.
- [better-auth-mongoose](https://github.com/AshwinSathian/better-auth-mongoose): a Mongoose adapter for Better Auth, endorsed by the Better Auth team. Auth collections become ordinary models, and `.populate()` works on them.

Apps:

- [booklet](https://github.com/AshwinSathian/booklet): Markdown in, shareable page out, for incident reports, ADRs and runbooks. You can publish from the web editor, an npm CLI, a [GitHub Action](https://github.com/AshwinSathian/publish-to-booklet) or an MCP server.
- [wayfarer](https://github.com/AshwinSathian/wayfarer): an API client that runs entirely in the browser. No account, and secrets are encrypted before they're stored.
- [brnr](https://github.com/AshwinSathian/brnr): end-to-end encrypted chats that delete themselves, using X3DH and the Double Ratchet (the protocol family Signal uses).

For working with coding agents:

- [workdeck](https://github.com/AshwinSathian/workdeck): a Claude Code plugin that splits a project into cards, one session and one reviewable pull request each.
- [humanize-writing-skill](https://github.com/AshwinSathian/humanize-writing-skill): a Claude Code skill that keeps Claude's prose from reading as machine-written.

Currently building [angularjs-migration-copilot](https://github.com/AshwinSathian/angularjs-migration-copilot), which moves AngularJS apps to Angular with deterministic codemods first. Every change, mechanical or not, has to get through the Angular compiler and a behaviour check before it's accepted.

### How I work

I want every claim in these repos to be something you can check. Weir traces each of its requirements to a test. The migration copilot is designed to report how much of a codebase was changed mechanically, how much with AI help, and how much it left for a person. And each README says what the project doesn't do as plainly as what it does.

### Recent writing

- [Three gaps in a caching layer, and the Go library I built to close them](https://ashwinsathian.com/writing/three-gaps-in-a-caching-layer-and-the-go-library-i-built-to-close-them)
- [The AI tells moved. My tool for avoiding them hadn't.](https://ashwinsathian.com/writing/the-ai-tells-moved-my-tool-for-avoiding-them-hadnt)
- [How do you check an answer when nobody agrees how to spell it?](https://ashwinsathian.com/writing/how-do-you-check-an-answer-when-nobody-agrees-how-to-spell-it)
- [Why Better Auth's MongoDB adapter can't populate() a Mongoose ref](https://ashwinsathian.com/writing/why-better-auths-mongodb-adapter-cant-populate-a-mongoose-ref)
