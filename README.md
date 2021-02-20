# React Basics

## Content
- What problems React can solve
- how React solves those problems under the hood
- What JSX is and how it translates to regular JavaScript function calls and objects
- Manage state with hooks
- Build forms

## Notes
### React DevTools
The React DevTools gives us components and profiler tab in our Developer Tools to give us a lot of insight into what our components are doing while we're developing them. Then we also have this indicator to tell us when we're using the development build of React versus the production build so we can make sure that our production application uses the production build.

#### Profiler tab
That will help us debug performance issues in our app. We can enable record while each component is rendering. We can also hide commits below a certain threshold. If a commit is really fast -- maybe it only takes five milliseconds to update the DOM -- then we can enable that.

#### Tip
One last pro tip I want to show you is if you open up the console while you have the components tab open -- you can do that by hitting the escape key --. You can type $r. That will give you the hooks, the props, and the type for the component that you have currently selected. This is actually very similar to the elements tab, where you can do a $0.
