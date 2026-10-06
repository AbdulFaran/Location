# Muskan Device Tracker — Vercel Web Dashboard

This is the web dashboard companion for the Android tracker.

## Fixing the Vercel 404
Upload/deploy this folder as the Vercel project root. It contains `index.html` at the root and a `vercel.json` route that sends requests to it.

## Google Maps
The current preview includes a map-style placeholder so it works without external keys. For production, replace the map container with Google Maps JavaScript API and configure the key through your Vercel environment.

## Backend
The buttons are UI/demo flows. For real multi-device tracking, connect them to a secure backend (Firebase/Supabase/custom API). The Android app must send GPS data only after the device owner accepts tracking and grants Android location permission.

## Privacy
IMEI/device identifiers are not a source of GPS location. Do not use this dashboard to track a device without the device owner's consent.
