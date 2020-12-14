# Modern TypeScript

*Developer notes about modern (2020) TypeScript.*

#### Rules

- Avoid `any`, use `unknown` instead.
- Avoid `Object` and `object`, use `{[key: string] : unknown}` instead.
- Avoid Enums, use Unions instead.

#### Whys

- [Any-vs-Unknown](https://mariusschulz.com/blog/the-unknown-type-in-typescript)
- [Object-vs-object-vs-{}](https://stackoverflow.com/questions/49464634/difference-between-object-and-in-typescript)
