# is-a.dev Registration — forgevii

This file is the exact content for your is-a.dev registration PR.

## Steps

1. Go to https://github.com/is-a-dev/register
2. Click **Fork**
3. In your fork, navigate to `domains/` folder
4. Click **Add file → Create new file**
5. Name the file: `forgevii.json`
6. Paste the JSON below
7. Click **Commit changes**
8. Click **Contribute → Open pull request**
9. Wait for approval (usually a few hours to a day)

## File Content — `forgevii.json`

```json
{
  "owner": {
    "username": "forgeVII",
    "email": ""
  },
  "record": {
    "CNAME": "forgevii.github.io"
  }
}
```

> **IMPORTANT:** Replace `email` with your GitHub account's noreply email. You can find it at:
> GitHub → Settings → Emails → "Keep my email addresses private" → the `@users.noreply.github.com` address.

## After Approval

Approval takes a few hours. Once the PR is merged:

1. Create a file named `CNAME` in this repo's root (with content `forgevii.is-a.dev`) and push
2. Go to repo **Settings → Pages → Custom domain** → enter `forgevii.is-a.dev` → Save
3. Wait for the DNS to propagate (a few minutes to an hour)
4. Your site is live at **https://forgevii.is-a.dev**

## Future Subdomains (Optional)

Later you can add project-specific subdomains by creating more JSON files:

- `tbas.forgevii.json` → `{"record": {"CNAME": "forgeVII.github.io"}}` (or point to a project page)
- `hotas.forgevii.json` → same pattern

Each needs a matching `CNAME` on the project's Pages site (project repo → Settings → Pages → Custom domain).
