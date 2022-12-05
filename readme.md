# SUPABASE LOCAL DEVELOPMENT
### Prerequisites
You should have signed up with Github.
You should have a supabase account.
Basic knowledge of git.

### Environment setup
Clone the repository
Install Docker, GIT and supabase CLI.
Login into supabase using
```bash
supabase login
```
This will provide a link [here](https://app.supabase.com/account/tokens) that you can follow to generate a supabase access token. 
Create a working directory for your project and change location to your directory.
Initialize the project's working directory into a git repository using.
```bash
git init
```
Initialize the working directory to a supabase project using the command.
```js
supabase init
```
Start your project by running 
```bash
supabase start
```
Note: In the *main.yaml* file, specify the right branch to perform the actions.