# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

 In this todo app we can see a  input field in which we can simply enter our todos task then we have add button to add task in list.If task can be done then simply tick the task and we can delete the task or edit the task.
We can face problem if we add empty input in list to solve this problem we add a condition on button to show visiblity when we have input otherwise it will disable.
We can also have problem when we add task it will added in list but if we refresh the page then it will remove so to solve this problem we use local storage to store the task when we refresh the page  it will not removed.
