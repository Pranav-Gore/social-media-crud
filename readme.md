🧩 STEP 1: Install Prerequisites (Skip if already done)
Make sure these are installed:

Tool	Command to Check	Install Link
Node.js	node -v	https://nodejs.org
npm	npm -v	Comes with Node
Angular CLI	ng version	npm install -g @angular/cli

social-media-crud/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   └── post/
│   │   │       ├── post.component.ts
│   │   │       ├── post.component.html
│   │   │       └── post.component.css
│   │   ├── models/
│   │   │   └── post.model.ts
│   │   ├── services/
│   │   │   └── post.service.ts
│   │   └── app.module.ts
│   │   └── app.component.ts / html / css

ng new social-media-crud
cd social-media-crud
ng generate component components/post
ng generate service services/post
