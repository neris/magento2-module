# Troubleshooting

## Stock Synchronization Issues

Our module uses the Magento cron schedule to synchronize. If your local Stockbase stock copy is not synchronizing 
properly (for example, if your `stockbase_stock` table is empty), please check your `cron_schedule` for error logs or 
messages reported by our module (job code prefix `stockbase_`).
