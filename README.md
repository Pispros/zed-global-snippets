# Zed Global Snippets

A comprehensive collection of 174 code snippets for JavaScript, TypeScript, React, Angular, Vue, PHP, Go, Rust, and Python, designed for the [Zed](https://zed.dev) code editor.

## Installation

1. **Copy the snippets file** to your Zed snippets directory:

   ```bash
   cp snippets.json ~/.config/zed/snippets/snippets.json
   ```

2. **Alternatively, open the snippets folder in Zed**:
   - Open the command palette (`Cmd+K` on macOS, `Ctrl+K` on Linux/Windows)
   - Run "Open Folder" and navigate to `~/.config/zed/snippets/`
   - Place the `snippets.json` file in this folder

3. **Restart Zed** if the snippets don't appear immediately.

## Usage

Type the prefix in your editor and press `Tab` or `Enter` to expand the snippet. Use `Tab` to navigate between placeholders.

## Quick Reference

### JavaScript

| Prefix | Description |
|--------|-------------|
| `af` | Arrow function |
| `afi` | Inline arrow function |
| `aaf` | Async arrow function |
| `aiife` | Async IIFE |
| `evth` | Event handler |
| `tc` | try/catch |
| `tcf` | try/catch/finally |
| `prom` | new Promise |
| `fetch` | fetch with await |
| `fetche` | fetch with error handling |
| `map` | Array map |
| `filter` | Array filter |
| `reduce` | Array reduce |
| `find` | Array find |
| `some` | Array some |
| `every` | Array every |
| `cl` | console.log |
| `cll` | console.log labeled |
| `ce` | console.error |
| `cw` | console.warn |
| `ctbl` | console.table |
| `imn` | Import named |
| `imd` | Import default |
| `imt` | Import type |

### React/JSX

| Prefix | Description |
|--------|-------------|
| `imr` | Import React |
| `imhooks` | Import React Hooks |
| `rfc` | React Functional Component |
| `rfcp` | React Functional Component with Props |
| `rac` | React Arrow Component |
| `racp` | React Arrow Component with Props |
| `us` | useState |
| `ust` | useState Typed |
| `ue` | useEffect |
| `uem` | useEffect on Mount |
| `ur` | useRef |
| `ucb` | useCallback |
| `um` | useMemo |
| `uctx` | useContext |
| `chook` | Custom Hook |
| `ctxprov` | Context + Provider |
| `rfwd` | React forwardRef |
| `frag` | JSX Fragment |
| `jsxmap` | JSX Map |
| `jsxif` | JSX Conditional |
| `jsxt` | JSX Ternary |
| `onch` | onChange Input |
| `onsub` | onSubmit Form |
| `usefetch` | useFetch Hook |

### TypeScript

| Prefix | Description |
|--------|-------------|
| `iface` | Interface |
| `ifacee` | Interface Extends |
| `ttype` | Type |
| `tobj` | Type Object |
| `tunion` | Union |
| `tinter` | Intersection |
| `tsenum` | Enum |
| `gfn` | Generic Function |
| `gaf` | Generic Arrow |
| `tguard` | Type Guard |
| `sat` | Satisfies |
| `tmap` | Mapped Type |
| `tcond` | Conditional Type |
| `tret` | ReturnType |
| `trec` | Record |
| `tpart` | Partial |
| `tomit` | Omit |
| `tpick` | Pick |
| `dmod` | Declare module |

### Angular

| Prefix | Description |
|--------|-------------|
| `ngcomp` | Component |
| `ngcompc` | Component OnPush |
| `ngsvc` | Service |
| `ngin` | Input |
| `ngout` | Output |
| `ngoninit` | ngOnInit |
| `ngondestroy` | ngOnDestroy |
| `ngpipe` | Pipe |
| `ngdir` | Directive |
| `nghttp` | HttpClient GET |
| `ngsig` | Signal |
| `ngcomputed` | Computed |
| `ngeffect` | Effect |

### Vue

| Prefix | Description |
|--------|-------------|
| `vsfc` | Vue SFC |
| `vref` | Vue ref |
| `vreact` | Vue reactive |
| `vcomp` | Vue computed |
| `vwatch` | Vue watch |
| `vwe` | Vue watchEffect |
| `vom` | Vue onMounted |
| `voum` | Vue onUnmounted |
| `vprops` | Vue defineProps |
| `vemits` | Vue defineEmits |
| `vexpose` | Vue defineExpose |
| `vprov` | Vue provide |
| `vinj` | Vue inject |
| `vcomposable` | Vue Composable |
| `vfor` | Vue v-for |
| `vif` | Vue v-if |
| `vmodel` | Vue v-model |

### PHP

| Prefix | Description |
|--------|-------------|
| `phpclass` | Class |
| `phpiface` | Interface |
| `phpabs` | Abstract Class |
| `phptrait` | Trait |
| `phpenum` | Enum |
| `phpfn` | Function |
| `phpaf` | Arrow Function |
| `phptc` | Try Catch |
| `phpns` | Namespace |
| `phpuse` | Use |
| `phpmap` | Array Map |
| `phpfilter` | Array Filter |
| `phpdd` | dd |
| `phpvd` | var_dump |

### Go

| Prefix | Description |
|--------|-------------|
| `gomain` | Main |
| `gofn` | Function |
| `gomethod` | Method |
| `gostruct` | Struct |
| `goiface` | Interface |
| `goerr` | Error Check |
| `goerrf` | Error Wrap |
| `goiferr` | Assign and Check Error |
| `gogo` | Goroutine |
| `gochan` | Channel |
| `gosel` | Select |
| `godefer` | Defer |
| `gofor` | For Range |
| `gotest` | Test Function |
| `gottable` | Table Test |
| `gohttp` | HTTP Handler |
| `gofmt` | Fmt Println |
| `gofmtf` | Fmt Printf |

### Rust

| Prefix | Description |
|--------|-------------|
| `rsfn` | Function |
| `rsafn` | Async Function |
| `rsstruct` | Struct |
| `rsderiv` | Struct Derive |
| `rsenum` | Enum |
| `rsimpl` | Impl |
| `rstrait` | Trait |
| `rsimpltr` | Impl Trait |
| `rsmatch` | Match |
| `rsiflet` | if let |
| `rswlet` | while let |
| `rsresult` | Result |
| `rsoption` | Option |
| `rsvec` | Vec |
| `rsvecm` | vec! macro |
| `rshmap` | HashMap |
| `rsclos` | Closure |
| `rsfor` | For Loop |
| `rspln` | println |
| `rsdbg` | dbg |
| `rstestmod` | Test Module |
| `rstestfn` | Test Function |

### Python

| Prefix | Description |
|--------|-------------|
| `pyfn` | Function |
| `pyafn` | Async Function |
| `pycls` | Class |
| `pydc` | Dataclass |
| `pydcf` | Dataclass Frozen |
| `pytd` | TypedDict |
| `pyprot` | Protocol |
| `pytc` | Try Except |
| `pytcf` | Try Except Finally |
| `pywith` | Context Manager |
| `pylc` | List Comprehension |
| `pydc2` | Dict Comprehension |
| `pygen` | Generator |
| `pylambda` | Lambda |
| `pymain` | Main Guard |
| `pyprop` | Property |
| `pyclsm` | Classmethod |
| `pystatic` | Staticmethod |
| `pyenum` | Enum |
| `pyp` | Print |
| `pypf` | Print f-string |
| `pyim` | Import |
| `pyassert` | Assert |

## Adding Your Own Snippets

You can extend this collection by editing the `snippets.json` file. The format follows the [Zed snippets specification](https://zed.dev/docs/snippets).

Example snippet structure:

```json
"Snippet Name": {
  "prefix": "prefix",
  "body": [
    "line 1",
    "line 2"
  ],
  "description": "Description of the snippet"
}
```

## Contributing

Feel free to submit pull requests with additional snippets or improvements to existing ones.

## License

MIT
