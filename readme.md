# NestJS Notebooks

<div align="right">

![Build](https://img.shields.io/github/actions/workflow/status/SagarBiswas-MultiHAT/NestJS-Notebooks/ci.yml?branch=main)
&nbsp;
![Release](https://img.shields.io/github/v/release/SagarBiswas-MultiHAT/NestJS-Notebooks)
&nbsp;
![Last Commit](https://img.shields.io/github/last-commit/SagarBiswas-MultiHAT/NestJS-Notebooks)
&nbsp;
![Issues](https://img.shields.io/github/issues/SagarBiswas-MultiHAT/NestJS-Notebooks)
&nbsp;
![License](https://img.shields.io/github/license/SagarBiswas-MultiHAT/NestJS-Notebooks)
&nbsp;
![Made with NestJS](https://img.shields.io/badge/made%20with-NestJS-7C3AED)

</div>

## Part 1: Fundamentals, REST APIs, Postman & Interview Prep

Excited to share my first NestJS Student Notebook; a beginner-to-intermediate guide covering fundamentals, real-world use cases, and interview preparation! 🚀

For anyone who doesn't know, NestJS is a TypeScript-based Node.js framework that basically fixes everything messy about Express. It gives your backend actual structure instead of letting everyone on the team do things differently.

> Here is everything I covered 👇

- **Introduction**: what NestJS actually is, why we need it, and how it compares to Express (spoiler: NestJS wins for big projects).
- **Installation**: setting up Node.js, npm, the NestJS CLI, creating your first project and running it on localhost:3000.
- **File & Folder Structure**: what every generated file does (main.ts, app.module.ts, app.controller.ts, app.service.ts and more).
- **Controllers**: the "front door" of your app. They receive HTTP requests and send responses back. covered decorators like @Controller(), @Get(), @Post() and how to generate them with the CLI.
- **Services**:  where the actual logic lives. calculations, data fetching, API calls — all goes here. also covered @Injectable() and why you should never put logic inside controllers.
- **Modules**: the container that groups everything for one feature together. think of it like a restaurant 🍽️; the module is the restaurant, controller is the waiter, service is the chef.
- **NestJS Architecture**: the full picture of how a request flows: Client → Controller → Service → Provider/DB → back to Client, and what each piece actually does.
- **Dependency Injection**: honestly, the most mind-blowing part. Instead of manually writing new SomeService() everywhere, NestJS automatically creates and provides it through the IoC Container. covered singleton behavior, loose coupling, and the water pipe analogy 🚿.
- **REST API & HTTP Methods + Postman**: what REST actually means, the difference between GET / POST / PUT / PATCH / DELETE, why PATCH ≠ PUT, what "stateless" means, and why Postman is better than the browser for testing APIs.
- **Building Full CRUD REST APIs**: put everything together and built a real Student API with all 5 HTTP methods, NotFoundException handling, Partial<> for PATCH, Object.assign(), splice(), and tested everything in Postman.

Interview prep questions are included at the end of every section too 🎯

- PDF: [NestJS Notebooks - Part 1](NestJS_Part-1.pdf)

If you are learning backend development or NestJS, I hope this helps! drop an issue if you have any questions 💬

Still learning, but sharing what I know because someone out there might need exactly this. Would love feedback from senior developers in the community! 

