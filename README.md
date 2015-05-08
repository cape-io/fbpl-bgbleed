# fbpl-bgbleed
Basic layout for FaceBook Pages — full screen background

FBPL » Facebook Pages Layout

This folder contains all CSS and images required by the layout of a facebook pages site. Ideologically this is built on the CSS Zen Garden model — the HTML stays the same, and only the CSS and "stylistically" required images change.

Images required by the CSS should go in the "public" folder.

Currently we like using LESS as our CSS preprocesser. app.less is currently the "master" file that is used to compile all the different CSS pieces into one, compressed file for production. You may add whatever additional .less files you need, just make sure you add them to app.less to make sure they are included in your production CSS.

a OOKB/CAPE project.
