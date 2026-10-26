# Robot Pilots

Home page for a series of small simulation pilots on one question: does a learned robot agent notice that
the world changed between looking and acting, or does it act on what it saw before?

Robot learning is often split into three directions (locomotion, navigation, manipulation); the plan is one
small pilot in each. Each pilot keeps its own repository and project page; this repository only holds the
home page (`index.html`, served by GitHub Pages).

| direction | pilot | status |
| --- | --- | --- |
| Navigation | [Stale World Pilot](https://laulauraluo.github.io/stale-world-pilot/) ([code](https://github.com/laulauraluo/stale-world-pilot)) | done |
| Manipulation | an object moves between looking and grasping | next |
| Locomotion | the ground changes after the robot has mapped it | planned |

To add a pilot: give it its own repository and page, then update its card in `index.html` (status tag, link)
and its row in the "Pilots" list. The three animations on the page are schematic, drawn in the browser with
plain JavaScript (no dependencies); they are not simulation output.
