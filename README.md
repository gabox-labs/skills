# Gabox skills

Agent skills for [Gabox](https://gabox.fun), a marketplace of token gacha
machines on Solana.

## gabox

Teaches your AI agent the Gabox public API: every call, the rules, the
errors, and who signs. Your agent reads machines, packs, draws and pulls,
and builds transactions for your own wallet to sign. It never holds a key.

```sh
npx skills add gabox-labs/skills -g
```

The same skill installs from the site too:

```sh
npx skills add https://gabox.fun -g
```

`-g` installs it for every project. Leave it out to install it in the
current project only.

The Gabox app generates `skills/gabox/SKILL.md` from its own API reference,
so please do not edit it by hand. Questions or fixes: hello@gabox.fun.

- API reference: https://gabox.fun/developers
- OpenAPI: https://actions.gabox.fun/v1/openapi.json
