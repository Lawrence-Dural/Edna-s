# MarkMan × Edna’s Pasalubong — Team Demo

This project contains the V5 interactive prototype as a **static Vercel site**.

## Deploy from Vercel

1. Create a private GitHub repository and upload `public/index.html` and `vercel.json` from this folder (preserve the `public` folder).
2. Go to https://vercel.com/new and import the repository.
3. Select Framework Preset: **Other**. Root Directory: repository root. Output Directory: `public`. No build command required.
4. Deploy. Copy the generated link and share it with your team.

## Deploy directly with the Vercel CLI

```bash
npm install -g vercel
cd MarkMan_Ednas_Vercel_Ready
vercel login
vercel --prod
```

## Important limitations

- All records are fictional demo data. Do not enter real client/customer/financial data.
- The prototype stores changes in **each browser's localStorage**. Your teammates will each see their own independent data and edits will NOT sync across devices.
- This is **not a secure live system**: no server, login, backend, shared database, or production POS/payment functions.
- By default, a Vercel deployment link can be opened by anyone who knows it. Configure deployment protection in Vercel if your plan supports it and the demo should be restricted.
- Excel exporter is prototype code. Verify exported workbooks in Microsoft Excel before showing them to the client.
