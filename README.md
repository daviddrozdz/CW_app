# based on assetz app

![Group 1 (1)](https://github.com/SHL-Digital-Practice/assetz/assets/62248969/a44bd4ff-f1b1-4506-9f10-681651e2c2d8)



# How to deal with the app

1. initialize new project
- npx nux@latest init app (app is the name)

2. naviagte to app folder
- cd app

3. install dependencies 
- npm install @nuxtjs/tailwindcss
- npm install nuxt-icon

4. run app
- npm run dev

5. write some code
- ...

6. install ngrok and save it near the project loction
- https://dashboard.ngrok.com/get-started/setup/windows

7. open terminal and exectute ngrok from the folder where it is stored
- for example ::: & "C:\LAPTOP\David\University\STOPNIEŃ II\IAAC\MaCAD_2023_2024\2nd MOD - BIM and Smart Construction\Digital Tools for Collaborative Workflows\Project\ngrok.exe" http 3000

8. Naviagte to the right folder and run dev in another window in terminal
- for example ::: C:\LAPTOP\David\University\STOPNIEŃ II\IAAC\MaCAD_2023_2024\2nd MOD - BIM and Smart Construction\Digital Tools for Collaborative Workflows\Project\CW_app\app> npm run dev

9. Setup superbase table with data
- https://supabase.com/dashboard/

10. write some code
- ...

11. create .env file in the app folder with 
- SUPABASE_URL = .....
- SUPABASE_KEY = .....

12. create new folder in the app for the typescript
- "types"

12. generate some typescript in the terminal in the right location (project-id should be from the .env file)
- for example ::: C:\LAPTOP\David\University\STOPNIEŃ II\IAAC\MaCAD_2023_2024\2nd MOD - BIM and Smart Construction\Digital Tools for Collaborative Workflows\Project\CW_app\app> npx supabase gen types typescript --project-id "hlgvcvjmnacquxutxflq" --schema public > types/database.types.ts