# Hi, I'm Aryan

I'm a first-year Software Engineering (co-op) student at McGill, in Montreal. I made my first website in early 2023, a recipe page for The Odin Project, and I've been building things ever since.

These days I mostly work on backends: APIs, databases, and the parts of an app nobody sees until they break.

## Why backend

A file upload looks like one button. Building drive-clone showed me how many decisions sit behind it. What do you name the file on disk? Not whatever the user typed, or two people's `notes.pdf` collide and someone tries `../../`. Where does the metadata live, and what happens to it if the server restarts? When someone deletes a folder, what happens to everything inside it? And who is allowed to see any of it?

None of those show up on a screen. But get one wrong and a user loses a file, or sees one that isn't theirs. I like work where the stakes are real but hidden, and where you can only be sure it's right by thinking it through carefully.

It's also the closest thing in programming to the math I tutored at Dawson. A folder tree is a recursive structure. A permission check is a rule that has to hold on every route, not most of them, the same way a proof can't hold for "most" cases.

## What I'm building

**[drive-clone](https://github.com/aryankarayi/drive-clone)**: a file storage backend in FastAPI, aiming for the core of Google Drive. Nested folders, uploads and downloads already work, and files are stored under random UUIDs instead of their real names. Next up: PostgreSQL, JWT logins, ownership checks on every route, then sharing with view and edit permissions.

**[grover-brute-force-search](https://github.com/aryankarayi/grover-brute-force-search)**: a Streamlit app my team of four built during the Quantum Ready program. It pits Grover's search algorithm (written in Qiskit) against classical brute force on a list of common passwords. On 1,024 passwords, Grover needed 25 oracle calls to find the target with 99.95% probability. Brute force expects about 512 checks. [Try the demo](https://grover-brute-force-search.streamlit.app/).

## How I got here

- **2023:** HTML, CSS and JavaScript through The Odin Project. [etch-a-sketch](https://github.com/aryankarayi/etch-a-sketch) and [rock-paper-scissors](https://github.com/aryankarayi/rock-paper-scissors) are from that time.
- **Harvard's CS50x and CS50P:** where Python became my main language.
- **2026:** the Quantum Ready program (Numana & AI Launch Lab), then McGill.
- **Ongoing:** algorithm practice in [neetcode-submissions](https://github.com/aryankarayi/neetcode-submissions) and [Exercism](https://github.com/aryankarayi/Exercism).

## Away from the keyboard

At Dawson College I co-founded a Mathematics & Philosophy club that grew to 57 members. I gave sessions on the number *e*, behaviourism and cybernetics, and convinced math professors to come in as guest speakers. I was also a peer tutor at Dawson, helping other students through Calculus I, II and III and Linear Algebra, and before that I taught beginner piano. Explaining something to someone else is still the fastest way I know to find out whether I actually understand it.

## Right now

- Looking for a **Summer 2027 co-op term** in software, anywhere in Canada (on-site, hybrid or remote)
- Moving drive-clone from in-memory storage to PostgreSQL

[LinkedIn](https://linkedin.com/in/aryan-karayi) · aryankarayi@gmail.com
