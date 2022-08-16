# sample-clasp-typescript

## やったこと

1. clasp のインストール

   ```
   npm install -g @google/clasp
   clasp -v
   2.4.1
   clasp login
   ```

2. clasp で、Google ログイン

   ```sh
   clasp login
   ```

3. clasp セットアップ

   ```sh
   clasp create --type standalone
   ```

4. npm init

   ```
   npm init
   ```

5. `@types/google-apps-script` をインストール

   ```
   npm i -S @types/google-apps-script
   ```

6. `tsconfig.json` 作成
7. `src/hello.ts` 作成
8. clasp を利用して、デプロイ

   ```sh
   clasp push
     └─ sample-clasp-typescript/appsscript.json
     └─ sample-clasp-typescript/src/hello.ts
     Pushed 2 files.
   ```

9. マイドライブにある `Sample-clasp-typescript` にある `src/hello.gs` で、実行とかして試してみる。
