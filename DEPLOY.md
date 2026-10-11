# Deploy the gallery on Vercel

1. In Vercel, choose **Add New → Project** and import `nivitra/ssss`.
2. Keep the root directory at the repository root and the framework preset **Other**.
3. Deploy. The included `vercel.json` disables install/build commands and serves the root directory.

No environment variables, API keys, database, package install or application backend are required. The repository contains the static gallery and its original PNG screenshots; it is not the runnable iPhone app or Kulture backend.

After deployment, open the project URL and verify a screenshot, the search filter and a flow step. Full-resolution originals are under `images/`; the gallery also works offline by opening `index.html`.

Configuration reference: [Vercel project configuration](https://vercel.com/docs/project-configuration/vercel-json).
