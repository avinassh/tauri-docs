# path

The path module provides utilities for working with file and directory paths.

This package is also accessible with `window.__TAURI__.path` when [`build.withGlobalTauri`](https://tauri.app/v1/api/config/#buildconfig.withglobaltauri) in `tauri.conf.json` is set to `true`.

It is recommended to allowlist only the APIs you use for optimal bundle size and security.

## Enumerations

### `BaseDirectory`

**Since**: 2.0.0

#### Enumeration Members

| Name | Type | Defined in |
| :------ | :------ | :------ |
| <div class="anchor-with-padding" id="path.BaseDirectory.AppCache"><a href="#path.BaseDirectory.AppCache">`AppCache`</a></div> | `16` | [path.ts:35](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L35) |
| <div class="anchor-with-padding" id="path.BaseDirectory.AppConfig"><a href="#path.BaseDirectory.AppConfig">`AppConfig`</a></div> | `13` | [path.ts:32](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L32) |
| <div class="anchor-with-padding" id="path.BaseDirectory.AppData"><a href="#path.BaseDirectory.AppData">`AppData`</a></div> | `14` | [path.ts:33](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L33) |
| <div class="anchor-with-padding" id="path.BaseDirectory.AppLocalData"><a href="#path.BaseDirectory.AppLocalData">`AppLocalData`</a></div> | `15` | [path.ts:34](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L34) |
| <div class="anchor-with-padding" id="path.BaseDirectory.AppLog"><a href="#path.BaseDirectory.AppLog">`AppLog`</a></div> | `17` | [path.ts:36](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L36) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Audio"><a href="#path.BaseDirectory.Audio">`Audio`</a></div> | `1` | [path.ts:20](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L20) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Cache"><a href="#path.BaseDirectory.Cache">`Cache`</a></div> | `2` | [path.ts:21](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L21) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Config"><a href="#path.BaseDirectory.Config">`Config`</a></div> | `3` | [path.ts:22](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L22) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Data"><a href="#path.BaseDirectory.Data">`Data`</a></div> | `4` | [path.ts:23](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L23) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Desktop"><a href="#path.BaseDirectory.Desktop">`Desktop`</a></div> | `18` | [path.ts:38](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L38) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Document"><a href="#path.BaseDirectory.Document">`Document`</a></div> | `6` | [path.ts:25](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L25) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Download"><a href="#path.BaseDirectory.Download">`Download`</a></div> | `7` | [path.ts:26](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L26) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Executable"><a href="#path.BaseDirectory.Executable">`Executable`</a></div> | `19` | [path.ts:39](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L39) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Font"><a href="#path.BaseDirectory.Font">`Font`</a></div> | `20` | [path.ts:40](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L40) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Home"><a href="#path.BaseDirectory.Home">`Home`</a></div> | `21` | [path.ts:41](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L41) |
| <div class="anchor-with-padding" id="path.BaseDirectory.LocalData"><a href="#path.BaseDirectory.LocalData">`LocalData`</a></div> | `5` | [path.ts:24](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L24) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Picture"><a href="#path.BaseDirectory.Picture">`Picture`</a></div> | `8` | [path.ts:27](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L27) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Public"><a href="#path.BaseDirectory.Public">`Public`</a></div> | `9` | [path.ts:28](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L28) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Resource"><a href="#path.BaseDirectory.Resource">`Resource`</a></div> | `11` | [path.ts:30](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L30) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Runtime"><a href="#path.BaseDirectory.Runtime">`Runtime`</a></div> | `22` | [path.ts:42](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L42) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Temp"><a href="#path.BaseDirectory.Temp">`Temp`</a></div> | `12` | [path.ts:31](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L31) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Template"><a href="#path.BaseDirectory.Template">`Template`</a></div> | `23` | [path.ts:43](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L43) |
| <div class="anchor-with-padding" id="path.BaseDirectory.Video"><a href="#path.BaseDirectory.Video">`Video`</a></div> | `10` | [path.ts:29](https://github.com/tauri-apps/tauri/blob/28382fd/tooling/api/src/path.ts#L29) |

## Functions

### `appCacheDir`

> **appCacheDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the suggested directory for your app's cache files.
Resolves to `${cacheDir}/${bundleIdentifier}`, where `bundleIdentifier` is the value [`tauri.bundle.identifier`](https://tauri.app/v1/api/config/#bundleconfig.identifier) is configured in `tauri.conf.json`.

**Example**

```typescript
import { appCacheDir } from '@tauri-apps/api/path';
const appCacheDirPath = await appCacheDir();
```

**Since**: 1.2.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `appConfigDir`

> **appConfigDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the suggested directory for your app's config files.
Resolves to `${configDir}/${bundleIdentifier}`, where `bundleIdentifier` is the value [`tauri.bundle.identifier`](https://tauri.app/v1/api/config/#bundleconfig.identifier) is configured in `tauri.conf.json`.

**Example**

```typescript
import { appConfigDir } from '@tauri-apps/api/path';
const appConfigDirPath = await appConfigDir();
```

**Since**: 1.2.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `appDataDir`

> **appDataDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the suggested directory for your app's data files.
Resolves to `${dataDir}/${bundleIdentifier}`, where `bundleIdentifier` is the value [`tauri.bundle.identifier`](https://tauri.app/v1/api/config/#bundleconfig.identifier) is configured in `tauri.conf.json`.

**Example**

```typescript
import { appDataDir } from '@tauri-apps/api/path';
const appDataDirPath = await appDataDir();
```

**Since**: 1.2.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `appLocalDataDir`

> **appLocalDataDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the suggested directory for your app's local data files.
Resolves to `${localDataDir}/${bundleIdentifier}`, where `bundleIdentifier` is the value [`tauri.bundle.identifier`](https://tauri.app/v1/api/config/#bundleconfig.identifier) is configured in `tauri.conf.json`.

**Example**

```typescript
import { appLocalDataDir } from '@tauri-apps/api/path';
const appLocalDataDirPath = await appLocalDataDir();
```

**Since**: 1.2.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `appLogDir`

> **appLogDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the suggested directory for your app's log files.

#### Platform-specific

- **Linux:** Resolves to `${configDir}/${bundleIdentifier}/logs`.
- **macOS:** Resolves to `${homeDir}/Library/Logs/{bundleIdentifier}`
- **Windows:** Resolves to `${configDir}/${bundleIdentifier}/logs`.

**Example**

```typescript
import { appLogDir } from '@tauri-apps/api/path';
const appLogDirPath = await appLogDir();
```

**Since**: 1.2.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `audioDir`

> **audioDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's audio directory.

#### Platform-specific

- **Linux:** Resolves to [`xdg-user-dirs`](https://www.freedesktop.org/wiki/Software/xdg-user-dirs/)' `XDG_MUSIC_DIR`.
- **macOS:** Resolves to `$HOME/Music`.
- **Windows:** Resolves to `{FOLDERID_Music}`.

**Example**

```typescript
import { audioDir } from '@tauri-apps/api/path';
const audioDirPath = await audioDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `basename`

> **basename**(`path`: `string`, `ext?`: `string`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the last portion of a `path`. Trailing directory separators are ignored.

**Example**

```typescript
import { basename, resolveResource } from '@tauri-apps/api/path';
const resourcePath = await resolveResource('app.conf');
const base = await basename(resourcePath);
assert(base === 'app.conf');
```

**Since**: 1.0.0

**Parameters**

| Name | Type | Description |
| :------ | :------ | :------ |
| `path` | `string` | - |
| `ext?` | `string` | An optional file extension to be removed from the returned path. |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `cacheDir`

> **cacheDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's cache directory.

#### Platform-specific

- **Linux:** Resolves to `$XDG_CACHE_HOME` or `$HOME/.cache`.
- **macOS:** Resolves to `$HOME/Library/Caches`.
- **Windows:** Resolves to `{FOLDERID_LocalAppData}`.

**Example**

```typescript
import { cacheDir } from '@tauri-apps/api/path';
const cacheDirPath = await cacheDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `configDir`

> **configDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's config directory.

#### Platform-specific

- **Linux:** Resolves to `$XDG_CONFIG_HOME` or `$HOME/.config`.
- **macOS:** Resolves to `$HOME/Library/Application Support`.
- **Windows:** Resolves to `{FOLDERID_RoamingAppData}`.

**Example**

```typescript
import { configDir } from '@tauri-apps/api/path';
const configDirPath = await configDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `dataDir`

> **dataDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's data directory.

#### Platform-specific

- **Linux:** Resolves to `$XDG_DATA_HOME` or `$HOME/.local/share`.
- **macOS:** Resolves to `$HOME/Library/Application Support`.
- **Windows:** Resolves to `{FOLDERID_RoamingAppData}`.

**Example**

```typescript
import { dataDir } from '@tauri-apps/api/path';
const dataDirPath = await dataDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `delimiter`

> **delimiter**(): `string`

Returns the platform-specific path segment delimiter:
- `;` on Windows
- `:` on POSIX

**Since**: 2.0.0

**Returns: **`string`

### `desktopDir`

> **desktopDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's desktop directory.

#### Platform-specific

- **Linux:** Resolves to [`xdg-user-dirs`](https://www.freedesktop.org/wiki/Software/xdg-user-dirs/)' `XDG_DESKTOP_DIR`.
- **macOS:** Resolves to `$HOME/Desktop`.
- **Windows:** Resolves to `{FOLDERID_Desktop}`.

**Example**

```typescript
import { desktopDir } from '@tauri-apps/api/path';
const desktopPath = await desktopDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `dirname`

> **dirname**(`path`: `string`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the directory name of a `path`. Trailing directory separators are ignored.

**Example**

```typescript
import { dirname, appDataDir } from '@tauri-apps/api/path';
const appDataDirPath = await appDataDir();
const dir = await dirname(appDataDirPath);
```

**Since**: 1.0.0

**Parameters**

| Name | Type |
| :------ | :------ |
| `path` | `string` |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `documentDir`

> **documentDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's document directory.

**Example**

```typescript
import { documentDir } from '@tauri-apps/api/path';
const documentDirPath = await documentDir();
```

#### Platform-specific

- **Linux:** Resolves to [`xdg-user-dirs`](https://www.freedesktop.org/wiki/Software/xdg-user-dirs/)' `XDG_DOCUMENTS_DIR`.
- **macOS:** Resolves to `$HOME/Documents`.
- **Windows:** Resolves to `{FOLDERID_Documents}`.

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `downloadDir`

> **downloadDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's download directory.

#### Platform-specific

- **Linux**: Resolves to [`xdg-user-dirs`](https://www.freedesktop.org/wiki/Software/xdg-user-dirs/)' `XDG_DOWNLOAD_DIR`.
- **macOS**: Resolves to `$HOME/Downloads`.
- **Windows**: Resolves to `{FOLDERID_Downloads}`.

**Example**

```typescript
import { downloadDir } from '@tauri-apps/api/path';
const downloadDirPath = await downloadDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `executableDir`

> **executableDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's executable directory.

#### Platform-specific

- **Linux:** Resolves to `$XDG_BIN_HOME/../bin` or `$XDG_DATA_HOME/../bin` or `$HOME/.local/bin`.
- **macOS:** Not supported.
- **Windows:** Not supported.

**Example**

```typescript
import { executableDir } from '@tauri-apps/api/path';
const executableDirPath = await executableDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `extname`

> **extname**(`path`: `string`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the extension of the `path`.

**Example**

```typescript
import { extname, resolveResource } from '@tauri-apps/api/path';
const resourcePath = await resolveResource('app.conf');
const ext = await extname(resourcePath);
assert(ext === 'conf');
```

**Since**: 1.0.0

**Parameters**

| Name | Type |
| :------ | :------ |
| `path` | `string` |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `fontDir`

> **fontDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's font directory.

#### Platform-specific

- **Linux:** Resolves to `$XDG_DATA_HOME/fonts` or `$HOME/.local/share/fonts`.
- **macOS:** Resolves to `$HOME/Library/Fonts`.
- **Windows:** Not supported.

**Example**

```typescript
import { fontDir } from '@tauri-apps/api/path';
const fontDirPath = await fontDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `homeDir`

> **homeDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's home directory.

#### Platform-specific

- **Linux:** Resolves to `$HOME`.
- **macOS:** Resolves to `$HOME`.
- **Windows:** Resolves to `{FOLDERID_Profile}`.

**Example**

```typescript
import { homeDir } from '@tauri-apps/api/path';
const homeDirPath = await homeDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `isAbsolute`

> **isAbsolute**(`path`: `string`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`boolean`\>

Returns whether the path is absolute or not.

**Example**

```typescript
import { isAbsolute } from '@tauri-apps/api/path';
assert(await isAbsolute('/home/tauri'));
```

**Since**: 1.0.0

**Parameters**

| Name | Type |
| :------ | :------ |
| `path` | `string` |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`boolean`\>

### `join`

> **join**(...`paths`: `string`[]): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Joins all given `path` segments together using the platform-specific separator as a delimiter, then normalizes the resulting path.

**Example**

```typescript
import { join, appDataDir } from '@tauri-apps/api/path';
const appDataDirPath = await appDataDir();
const path = await join(appDataDirPath, 'users', 'tauri', 'avatar.png');
```

**Since**: 1.0.0

**Parameters**

| Name | Type |
| :------ | :------ |
| `...paths` | `string`[] |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `localDataDir`

> **localDataDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's local data directory.

#### Platform-specific

- **Linux:** Resolves to `$XDG_DATA_HOME` or `$HOME/.local/share`.
- **macOS:** Resolves to `$HOME/Library/Application Support`.
- **Windows:** Resolves to `{FOLDERID_LocalAppData}`.

**Example**

```typescript
import { localDataDir } from '@tauri-apps/api/path';
const localDataDirPath = await localDataDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `normalize`

> **normalize**(`path`: `string`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Normalizes the given `path`, resolving `'..'` and `'.'` segments and resolve symbolic links.

**Example**

```typescript
import { normalize, appDataDir } from '@tauri-apps/api/path';
const appDataDirPath = await appDataDir();
const path = await normalize(appDataDirPath, '..', 'users', 'tauri', 'avatar.png');
```

**Since**: 1.0.0

**Parameters**

| Name | Type |
| :------ | :------ |
| `path` | `string` |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `pictureDir`

> **pictureDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's picture directory.

#### Platform-specific

- **Linux:** Resolves to [`xdg-user-dirs`](https://www.freedesktop.org/wiki/Software/xdg-user-dirs/)' `XDG_PICTURES_DIR`.
- **macOS:** Resolves to `$HOME/Pictures`.
- **Windows:** Resolves to `{FOLDERID_Pictures}`.

**Example**

```typescript
import { pictureDir } from '@tauri-apps/api/path';
const pictureDirPath = await pictureDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `publicDir`

> **publicDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's public directory.

#### Platform-specific

- **Linux:** Resolves to [`xdg-user-dirs`](https://www.freedesktop.org/wiki/Software/xdg-user-dirs/)' `XDG_PUBLICSHARE_DIR`.
- **macOS:** Resolves to `$HOME/Public`.
- **Windows:** Resolves to `{FOLDERID_Public}`.

**Example**

```typescript
import { publicDir } from '@tauri-apps/api/path';
const publicDirPath = await publicDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `resolve`

> **resolve**(...`paths`: `string`[]): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Resolves a sequence of `paths` or `path` segments into an absolute path.

**Example**

```typescript
import { resolve, appDataDir } from '@tauri-apps/api/path';
const appDataDirPath = await appDataDir();
const path = await resolve(appDataDirPath, '..', 'users', 'tauri', 'avatar.png');
```

**Since**: 1.0.0

**Parameters**

| Name | Type |
| :------ | :------ |
| `...paths` | `string`[] |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `resolveResource`

> **resolveResource**(`resourcePath`: `string`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Resolve the path to a resource file.

**Example**

```typescript
import { resolveResource } from '@tauri-apps/api/path';
const resourcePath = await resolveResource('script.sh');
```

**Since**: 1.0.0

**Parameters**

| Name | Type | Description |
| :------ | :------ | :------ |
| `resourcePath` | `string` | The path to the resource.<br/>Must follow the same syntax as defined in `tauri.conf.json > tauri > bundle > resources`, i.e. keeping subfolders and parent dir components (`../`). |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

The full path to the resource.

### `resourceDir`

> **resourceDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the application's resource directory.
To resolve a resource path, see the [[resolveResource | `resolveResource API`]].

**Example**

```typescript
import { resourceDir } from '@tauri-apps/api/path';
const resourceDirPath = await resourceDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `runtimeDir`

> **runtimeDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's runtime directory.

#### Platform-specific

- **Linux:** Resolves to `$XDG_RUNTIME_DIR`.
- **macOS:** Not supported.
- **Windows:** Not supported.

**Example**

```typescript
import { runtimeDir } from '@tauri-apps/api/path';
const runtimeDirPath = await runtimeDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `sep`

> **sep**(): `string`

Returns the platform-specific path segment separator:
- `\` on Windows
- `/` on POSIX

**Since**: 2.0.0

**Returns: **`string`

### `tempDir`

> **tempDir**(`path`: `string`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns a temporary directory.

**Example**

```typescript
import { tempDir } from '@tauri-apps/api/path';
const temp = await tempDir();
```

**Since**: 2.0.0

**Parameters**

| Name | Type |
| :------ | :------ |
| `path` | `string` |

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `templateDir`

> **templateDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's template directory.

#### Platform-specific

- **Linux:** Resolves to [`xdg-user-dirs`](https://www.freedesktop.org/wiki/Software/xdg-user-dirs/)' `XDG_TEMPLATES_DIR`.
- **macOS:** Not supported.
- **Windows:** Resolves to `{FOLDERID_Templates}`.

**Example**

```typescript
import { templateDir } from '@tauri-apps/api/path';
const templateDirPath = await templateDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

### `videoDir`

> **videoDir**(): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>

Returns the path to the user's video directory.

#### Platform-specific

- **Linux:** Resolves to [`xdg-user-dirs`](https://www.freedesktop.org/wiki/Software/xdg-user-dirs/)' `XDG_VIDEOS_DIR`.
- **macOS:** Resolves to `$HOME/Movies`.
- **Windows:** Resolves to `{FOLDERID_Videos}`.

**Example**

```typescript
import { videoDir } from '@tauri-apps/api/path';
const videoDirPath = await videoDir();
```

**Since**: 1.0.0

**Returns: **[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`string`\>
