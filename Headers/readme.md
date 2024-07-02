- Place header file in ROMVault's main directory.
- Insert this at the bottom of the header of the DAT: `<clrmamepro header="No-Intro_NES.xml"/>`

Example:
```
	<header>
		<id>007</id>
		<name>007 - Lost Level Archive - Nintendo - Famicom - Nintendo Entertainment System</name>
		<description>Nintendo - Famicom - Nintendo Entertainment System</description>
		<version>v20240702</version>
		<author>televandalist</author>
		<homepage>Lost Level Archive</homepage>
		<url>https://www.github.com/televandalist/lost-level-archive</url>
		<clrmamepro forcenodump="required"/>
		<clrmamepro header="No-Intro_NES.xml"/>
	</header>
```