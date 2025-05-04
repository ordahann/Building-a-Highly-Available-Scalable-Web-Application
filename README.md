# Building a Highly Available Scalable Web Application
> Student Records Web Application
### Students
- Roni Ronen
- Or Dahan

## 🛠️ How to run locally

1. Clone the repository
2. Run `npm install`
3. Make sure you have a `.env` file or manually insert your DB credentials for local testing (not used in AWS)
4. Run the app with `node index.js`

## 🌐 Deployment

In AWS, the app fetches DB credentials from Secrets Manager and connects to RDS.

## Folder structure

- `index.js`: Main entry point
- `app/`: Application logic
- `views/`: HTML views
- `public/`: Static assets
