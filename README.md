loja-de-pranchas/
│
├── src/
│   ├── controllers/
│   │   └── pranchaController.ts
│   ├── models/
│   │   └── pranchaModel.ts
│   ├── repositories/
│   │   └── pranchaRepository.ts
│   ├── routes/
│   │   └── pranchaRoutes.ts
│   └── server.ts
├── package.json
├── tsconfig.json
├── README.md
└── .gitignore
{
  "name": "loja-de-pranchas",
  "version": "1.0.0",
  "main": "dist/server.js",
  "scripts": {
    "start": "tsc && node dist/server.js",
    "dev": "tsc && nodemon dist/server.js"
  },
  "dependencies": {
    "express": "^4.17.1",
    "joi": "^17.6.0"
  },
  "devDependencies": {
    "typescript": "^4.5.2",
    "nodemon": "^2.0.15"
  }
}
{
  "compilerOptions": {
    "target": "ES6",
    "module": "commonjs",
    "strict": true,
    "esModuleInterop": true,
    "skipLibCheck": true,
    "forceConsistentCasingInFileNames": true,
    "outDir": "./dist"
  },
  "include": ["src/**/*"]
}
