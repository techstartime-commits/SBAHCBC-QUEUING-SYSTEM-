# SBAHCBC Queuing System

This folder is ready to publish with GitHub Pages.

## Files

- `index.html` - the queuing system web page.
- `.nojekyll` - tells GitHub Pages to serve the files exactly as they are.

## Publish On GitHub Pages

1. Create a new GitHub repository.
2. Upload the files from this folder to the repository root.
3. Open the repository settings.
4. Go to **Pages**.
5. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
6. Click **Save**.
7. GitHub will show the public website link after deployment finishes.

## Important Note

This version stores queue data in the browser using local storage. It works online, but each computer or phone will keep its own data. If you need all devices to share the same live queue, the next step is to connect the system to a shared backend/database.
