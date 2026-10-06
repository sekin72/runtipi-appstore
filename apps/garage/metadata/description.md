# Garage

Lightweight S3-compatible object storage. The app's main port serves the **web endpoint** (public, read-only bucket hosting). The **S3 API** is published on port 3900 for uploads.

Before first start, place a `garage.toml` in `data/config/` inside the app's data directory.
