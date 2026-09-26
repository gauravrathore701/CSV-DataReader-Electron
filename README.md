# CSV DataReader (Electron)

A desktop app for reading CSV files, built with ElectronJS. Open a file
and the rows are rendered in a scrollable table — no spreadsheet, no
upload, nothing leaves the machine.

## Stack

- ElectronJS — `main.js` (main process), `preload.js` (context bridge)
- Vanilla JavaScript + HTML in `renderer/`

## Running it

```bash
npm install
npm start
```

`data.csv` in the repo root is a sample file to try it against.

## Related

[CSV-DataReader-Tabs](https://github.com/gauravrathore701/CSV-DataReader-Tabs)
is the follow-up, which opens several CSVs side by side in tabs.
