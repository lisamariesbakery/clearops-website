# ClearOps Consulting website

Single-page branded landing site for clearopsmi.com.

## Local preview

Serve the `public` folder:

```
python3 -m http.server 8080 --directory public
```

Then open http://localhost:8080

## Deploy

This is a Render static site. The source must be in a GitHub, GitLab, or Bitbucket repository that the Render workspace can clone. After the repo exists, create the static site with:

- Name: clearops-website
- Build command: `echo "No build step"`
- Publish path: `public`
- Or apply `render.yaml` as a Blueprint

Point DNS only after Render reports the required records. Do not change Squarespace DNS until those records are confirmed.
