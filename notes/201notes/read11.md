#Class 11 Reading

This is important for creating better responsive websites that are more modern and not so "GeoCities" or "MySpace" like.

## Audio Video

1. The major shift from the early 2000s has been from proprietary video and audio formats with software that user may not have installed to widely adopted MP4 and and WebM have now become standard via the use of HTML5 on modern browsers without the need for plugins.
2. src is just like the src for inserting an img into an HTML file, it directs the browser where to look for the A/V files. Additionally, the controls allows the user to gain access to video controls like mute and volume or turning off or on subtitles.
3. Fallback content is important so you can describe what the video should have been and to give the user a direct link to where the video is hosted in case their browser can't play the file.
4. In the bustling town of Webville, best friends Video Tag and Audio Tag used to be inseparable. Video Tag, the captivating storyteller, and Audio Tag, the master of melodies, brought life to every webpage they graced. However, when Video Tag discovered he could embed audio within himself, thanks to the MP4 and WebM containers, things began to change.  Video Tag started to take center stage more often, sharing his tales with his own accompanying audio. Audio Tag, once Video Tag's indispensable companion, started to feel neglected. He watched from the sidelines as Video Tag dazzled the audience all by himself, his own talents seemingly forgotten. But Audio Tag knew his worth. He understood that standalone audio had its own unique power to engage, to convey information, and to create an ambiance. He patiently awaited the day when the subtle whispers of a podcast, the soothing strumming of an acoustic song, or the critical alerts of a notification sound would require his unique touch. And when that day came, he was ready, proving that even in a world of dazzling visuals, the power of pure audio should never be underestimated.

## Grid

1. Grid differs from Flex in that it allows much more ganular control of the distribution and placement of items within the browser viewport. For large and two-dimensional pages grid would be the best choice for the basic structure of the page, then use flex for individual items within the grid structure.
2. The Gric Container is the parent element to Grid Item, which is just a single element within the Grid Container. Which is usually just a cell within a specific row or column. Grid Line is the lines that separate the grid items into rows and columns, they are named and can be explicity stated to be where a piece of content should be placed.

## Responsive Images

1. Responsive images are important for making websites appealing, but also for ensuring the important parts of a webapge are visible and that unresponsive images aren't hampering the users experience. Difference screen siezs need different resolutions so webpage maintain their ratio so there can be some semblance of conssitency when viewing a webpage on mobile devices or on a desktop.
2. The srcset attribute is used to specift different image files for different viewport resolutions. It lets the browser choose the best version of an image for itself rather than the site creator. The sizes attribute directs the browser to display a certain image a specific width range for each file included. That way the browser can choose the appropriate image for the resolution of the screen it's displaying on, and whether or not it needs to download the higher resolution image or not.
3. The use of srcset let's the browser choose the more efficient file size for the resolution which decreases page loading time and bandwidth usage. It's also much simpler, and requires almost no maintenace, just the same file at different resolutions. Also a fancy thing called <picture> and <media> element it can be used to display different photos at differing viewport sizes instead of just scaling the same image. JavaScript and CSS are more complex to implement these things.
