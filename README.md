# reproduce

see https://vuetifyjs.com/en/getting-started/installation/#get-started-with-vuetify-3
Using Vite & NPM & Typescript Support

npm create vuetify


√ Project name: ... vuetify352_test
√ Which preset would you like to install? » Essentials (Vuetify, VueRouter, Pinia)
√ Use TypeScript? ... No / Yes » Yes
√ Would you like to install dependencies with yarn, npm, pnpm, or bun? » npm

npm install

npm run build


Output:
``
> vuetify352_test@0.0.0 build
> vue-tsc --noEmit && vite build

node_modules/@vitejs/plugin-vue/dist/index.d.ts:25:52 - error TS2344: Type '"defineModel" | "hoistStatic" | "fs" | "globalTypeFiles" | "babelParserPlugins" | "propsDestructure" | "reactivityTransform"' does not satisfy the constraint 'keyof SFCScriptCompileOptions'.
  Type '"defineModel"' is not assignable to type 'keyof SFCScriptCompileOptions'.

25     script?: Partial<Pick<SFCScriptCompileOptions, 'babelParserPlugins' | 'globalTypeFiles' | 'defineModel' | 'propsDestructure' | 'fs' | 'reactivityTransform' | 'hoistStatic'>>;
                                                      ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

node_modules/vite/dist/node/index.d.ts:843:22 - error TS2420: Class 'import("vuetify352_test/node_modules/vite/dist/node/index").FSWatcher' incorrectly implements interface 'import("fs").FSWatcher'.
  Type 'FSWatcher' is missing the following properties from type 'FSWatcher': ref, unref

843 export declare class FSWatcher extends EventEmitter implements fs.FSWatcher {
                         ~~~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1127:18 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1127     }, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Record<string, any>, vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & {
                      ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1164:18 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1164     }, () => JSX.Element, {}, {}, {}, {}>;
                      ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1181:14 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1181 }, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Record<string, any>, string, {}, {}, string, vue.SlotsType<Partial<{
                  ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1212:20 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1212     }>>, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {}, vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & Readonly<vue.ExtractPropTypes<{
                        ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1235:20 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1235     }>>, () => JSX.Element, {}, {}, {}, {}>;
                        ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1247:16 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1247 }>>, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {}, string, {}, {}, string, {}> & vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & FilterPropsOptions<{
                    ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1274:20 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1274     }>>, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {}, vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & Readonly<vue.ExtractPropTypes<{
                        ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1297:20 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1297     }>>, () => JSX.Element, {}, {}, {}, {}>;
                        ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1309:16 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1309 }>>, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {}, string, {}, {}, string, {}> & vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & FilterPropsOptions<{
                    ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1336:20 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1336     }>>, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {}, vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & Readonly<vue.ExtractPropTypes<{
                        ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1359:20 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1359     }>>, () => JSX.Element, {}, {}, {}, {}>;
                        ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:1371:16 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

1371 }>>, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {}, string, {}, {}, string, {}> & vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & FilterPropsOptions<{
                    ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:2140:26 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

2140     }, () => false | JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {
                              ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:2309:26 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

2309     }, () => false | JSX.Element, {}, {}, {}, {
                              ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:2388:22 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

2388 }, () => false | JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {
                          ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:16030:26 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

16030     }, () => false | JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {
                               ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:16293:26 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

16293     }, () => false | JSX.Element, {}, {}, {}, {
                               ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:16420:22 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

16420 }, () => false | JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {
                           ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:26983:18 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

26983     }, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {
                       ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:27104:18 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

27104     }, () => JSX.Element, {}, {}, {}, {
                       ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:27161:14 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

27161 }, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, {
                   ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:35039:23 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

35039     } & {}, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Omit<{
                            ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:35086:23 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

35086     } & {}, () => JSX.Element, {}, {}, {}, {
                            ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:35107:19 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

35107 } & {}, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Omit<{
                        ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:35839:18 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

35839     }, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Record<string, any>, vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & {
                       ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:35894:18 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

35894     }, () => JSX.Element, {}, {}, {}, {
                       ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:35923:14 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

35923 }, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Record<string, any>, string, {
                   ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:61001:16 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

61001     }>[] | JSX.Element | undefined, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Record<string, any>, vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & {
                     ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:61050:16 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

61050     }>[] | JSX.Element | undefined, {}, {}, {}, {
                     ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:61076:12 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

61076 }>[] | JSX.Element | undefined, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Record<string, any>, string, {
                 ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:64389:18 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

64389     }, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Record<string, any>, vue.VNodeProps & vue.AllowedComponentProps & vue.ComponentCustomProps & {} & {
                       ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:64422:18 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

64422     }, () => JSX.Element, {}, {}, {}, {}>;
                       ~~~~~~~

node_modules/vuetify/lib/components/index.d.mts:64437:14 - error TS2694: Namespace 'global.JSX' has no exported member 'Element'.

64437 }, () => JSX.Element, unknown, {}, {}, vue.ComponentOptionsMixin, vue.ComponentOptionsMixin, Record<string, any>, string, {}, {}, string, vue.SlotsType<Partial<{        
                   ~~~~~~~

node_modules/vuetify/lib/index.d.mts:2:29 - error TS2300: Duplicate identifier 'ComponentPublicInstance'.

2 import { Ref, DeepReadonly, ComponentPublicInstance, JSXComponent, PropType, CSSProperties, App } from 'vue';
                              ~~~~~~~~~~~~~~~~~~~~~~~

node_modules/vuetify/lib/index.d.mts:479:15 - error TS2300: Duplicate identifier 'ComponentPublicInstance'.

479 import type { ComponentPublicInstance, FunctionalComponent, UnwrapNestedRefs, VNodeChild } from 'vue'
                  ~~~~~~~~~~~~~~~~~~~~~~~


Found 37 errors in 4 files.

Errors  Files
     1  node_modules/@vitejs/plugin-vue/dist/index.d.ts:25
     1  node_modules/vite/dist/node/index.d.ts:843
    33  node_modules/vuetify/lib/components/index.d.mts:1127
     2  node_modules/vuetify/lib/index.d.mts:2
``