RB Site Map, standalone website
================================

What is in this folder
  index.html   the map tool
  data/        the base map: aerial image pieces, property boundary, ground elevations

Put it on GitHub (free account)
  1. Sign in at github.com. Click the + at top right, New repository.
     Name it, for example, rb-site-map. Choose Public. Click Create repository.
     (On a free account the website only works from a Public repository.)
  2. On the new repository page click "uploading an existing file".
     Drag index.html and the whole data folder into the page. Wait for all
     files to finish, then click Commit changes.
  3. Go to Settings, then Pages. Under "Build and deployment" set Source to
     "Deploy from a branch", Branch to "main" and folder to "/ (root)". Save.
  4. After a minute or two the Pages screen shows the address, in the form
     https://YOUR-USERNAME.github.io/rb-site-map/
     That address is what you give to people.

How people use it
  - The page opens with the clean base map every time.
  - What they draw stays in their own browser on their own device.
  - Save (top right) downloads rb-site-drawings.json to their device.
  - Open brings that file back, on the same device or another one.
  - Nobody's drawings are uploaded anywhere or seen by anyone else.

Updating the tool later
  Replace index.html in the repository with the new one (Add file, Upload files,
  drag the new index.html, Commit). The data folder stays as it is.

Note
  It must be opened from the web address. Double-clicking index.html on a
  computer will not load the base map, because browsers block that.
