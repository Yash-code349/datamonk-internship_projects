What I Did in This Task
Initialized a Git Repo
I created a project folder and ran git init, which created a .git directory. This is where Git stores all its internal data.
Added and Committed Files
I used git add and git commit to track a file. After each commit, I checked inside .git/objects/ and saw new folders created with hashed filenames — these are Git's versioned object files.
Checked Object Details
Using the cat-file command, I explored how Git stores file contents (blobs) and commit metadata.

Created Summary File
I created this summary to show my understanding of how Git works internally beyond just basic commands.

What I Learned
Git doesn’t track files directly like a regular folder.
It uses a content-addressable system with SHA-1 hashes.
Every commit links to its parent — this forms a history tree.
The .git folder is the heart of the repository.
Blobs, Trees, and Commits are the building blocks of Git storage.

Final Thoughts
Before this, I used Git just for pushing and pulling code. But after exploring its internals, I now understand how it manages history and stores changes efficiently. It was interesting to peek inside Git’s engine room and realize how smart and lightweight it actually is.

This summary helped me realize that Git is not just a tool, it concern about safely and Work ethics.
