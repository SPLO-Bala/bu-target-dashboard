# BU Target Dashboard

## Normal daily update — only edit `data.csv`

Open `data.csv` in Excel. For the correct date row, enter the deposits collected by:

- `sp_isabel`
- `sofia`
- `christian`
- `pablo`

Also change the date on the `meta / Last Updated` row to the date of your latest update.

For content progress, update the `current` value on the `Content Target` row.

Save the file as CSV, keeping the exact filename `data.csv`.

Then in GitHub Desktop:

1. Review the changes.
2. Enter a summary such as `Update July 6 results`.
3. Click **Commit to main**.
4. Click **Push origin**.

Netlify will automatically redeploy from GitHub. You do not need to upload anything manually to Netlify.

## When to edit `index.html`

You normally do not need to edit `index.html`.

Only replace or edit it when changing the website design, calculations, names, targets, or layout.

## Initial installation of this version

Replace the existing repository files with:

- `index.html`
- `data.csv`
- `README.md`

Commit all three files once and push to `main`. After this one-time update, routine changes happen only in `data.csv`.
