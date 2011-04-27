var INFO =
<plugin name="spider" version="1.2"
    summary="split window"
		href="https://github.com/maksimr/spliter-penta"
    xmlns={NS}>
    <author email="rv.maksim@gmail.com">Ryzhikov Maksim</author>
    <project name="Pentadactyl" minVersion="1.0"/>
    <license href="http://www.gnu.org/licenses/gpl.html">GPL</license>

    <item>
        <tags>'spider' 'spid'</tags>
        <spec>:spider http://www.google.com</spec>
    </item>
    <p>
      This plugin allows you to split window, and load some page in current tab.
      It is implemented through frames.
    </p>

    <warning>
      If you reload the page then all the windows will disappear.
    </warning>

    <note>
		  YOU MUST HAVE _lib-app.js <link topic="https://github.com/maksimr/app-lib"> link </link>.
      If you do not specify an argument then the program will divide the current window
    </note>

		<p>OPTIONS:</p>
		<dl>
			<dt><oa>-pull(-P)</oa></dt><dd>This will allow you to "pull" open tab in the current page</dd>
			<dt><oa>-turn(-T) </oa></dt><dd>Expand and collapse the window</dd>
			<dt><oa>-close(-C)</oa></dt><dd>Close window</dd>
		</dl>

</plugin>;

