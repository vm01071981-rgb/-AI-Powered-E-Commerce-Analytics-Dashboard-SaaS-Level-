# TODO

## Step 1: Confirm current Mongo env expectation
- [x] Read `backend/app/config.py`
- [x] Verify startup hard-fail expects `MONGODB_URL`

## Step 2: Implement robust env var compatibility
- [x] Update `backend/app/config.py` to accept aliases: `MONGO_URI`, `MONGO_URL`, `DATABASE_URL`


## Step 3: Redeploy & verify
- [ ] In Render, trigger Manual Deploy → Clear Cache & Deploy
- [ ] Check backend logs for successful Mongo connection / no `MONGODB_URL must be set` error


