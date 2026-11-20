# Cabinet Door Builder

A free cut list calculator for five-piece shaker cabinet doors with a flat panel.

**Use it:** https://nagellams.github.io/cabinet-door-builder/

Type the cabinet opening, as a single door or a pair (overlay added all the way around, then the width split in half), and it gives you the finished door, the stiles, rails and panel, a 3D view and a to-scale drawing. You can add several doors to a job and copy the whole cut list. The door rules can be changed on the page. Without signing in, doors and rules are saved in your own browser only.

**Saved jobs:** an allowed Google account can sign in to keep every job online and reopen it later from any device. Jobs are stored in a Firebase project (Google sign-in + Cloud Firestore); the database rules in the Firebase console decide which accounts may sign in and save.

The whole app is `index.html`. It loads Three.js from cdnjs and its fonts from Google Fonts.
