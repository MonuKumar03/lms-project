# lms frontend

### setup instruction

1. clone the  project 
****
git clone https://github.com/MonuKumar03/lms-project.git
****
2. move into the directory
****
cd lms-project
****

3.install dependencies
****
npm install
****

4. run the server
****
npm run dev
****

### setup instructions for tailwind
Tailwind official instruction doc  (https://tailwindcss.com/docs/installation)
1. install tailwind 
****
npm install -D tailwindcss
****

2. create tailwind config file
****
npx tailwindcss init
****
3.Add file extension to tailwind config file in the content property
****
"./src/**/*.{html,js}"
****

4. add the tailwind directive at the top of the 'index.css' file
*****
@tailwind base;
@tailwind components;
@tailwind utilities;
***
### Adding plugins and dependencies
............
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
............