# @rbxts/types
TypeScript typings for the Roblox platform. Partially handwritten and partially automatically generated.

## Changelog
- **7/14/2025** - Added core method `GetFriendStatus(player: <Player>)` to `Player` interface.

## Installation
You can install `@rbxts/types` to your Roblox-TS project using the command:

`pnpm install -D --save-dev sily-lily/types`

Then, make sure `node_modules/@rbxts` is listed in your `compilerOptions.typeRoots` field in your project's `tsconfig.json` like so:

```json
{
	"compilerOptions": {
		"typeRoots": ["node_modules/@rbxts"]
	}
}
```
