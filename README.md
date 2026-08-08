# Shard

The resource pack that supports all custom features for the Shardcraft server.

## Release Instructions

1. Run the `Release Resource Pack` workflow from the repository’s Actions page.
1. Enter a release version, such as `12.0.0`.
1. Copy the archive URL and SHA-1 from the workflow summary.
1. Update the external server's `server.properties`:

```properties
resource-pack=https://github.com/<owner>/<repository>/releases/download/<version>/Shard_<version>.zip
resource-pack-sha1=<SHA-1 from the build step>
```

1. Restart the server or reload its configuration so clients receive the new pack.
