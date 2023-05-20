# SheetMusicCLI
Create Sheet music in your termninal!

| Name                                    	| Sheet Music TUI/CLI                                                                                                                                                                                                                                                                                                                                                                                                                                                      	|
|-----------------------------------------	|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Description:                            	| Create sheet music in your terminal by using the arrow keys to navigate lines or typing a letter to input a note, then picking the duration of the note from a little menu, you’re able to color code the lines from basic white                                                                                                                                                                                                                                         	|
| Purpose/Solution to:                    	| Lacking a way to create sheet music in your terminal                                                                                                                                                                                                                                                                                                                                                                                                                     	|
| Is performance required:                	| Not outside of file reading/writing. Everything else should be snappy regardless                                                                                                                                                                                                                                                                                                                                                                                         	|
| Lang:                                   	| Rust                                                                                                                                                                                                                                                                                                                                                                                                                                                                 	|
| Intended Users:                         	| Me                                                                                                                                                                                                                                                                                                                                                                                                                                                                       	|
| Tools/pkgs to Use:                      	|                                                                                                                                                                                                                                                                                                                                                                                                                                                                          	|
| Functional Design ↳(How does it work?): 	| Use arrow keys to navigate  Use keyboard to place notes <br/>↳ has dropdown to select what the note is (preferably a vert flyout)   <br/><br/>Saves to <filetype> <br/>↳ Name File  <br/>↳ Browse Files  <br/>↳ Delete Files <br/>↳ Rename Files  <br/><br/>Loads from <filetype> <br/>↳ Can practice w/ this by reading a config file  <br/><br/>Audio playback of the notes <br/>↳ Midi? <br/>↳ WAV alternative?  <br/><br/>Reads config file <br/> ↳ json or yaml?  <br/><br/>Music Features <br/>↳ hello? ? ?  <br/>↳ Octaves <br/>↳ Time signature  <br/>↳ note length  <br/>↳ Scroll Measures 	|
| Absolute Requirements:                  	| Must have home menu that at least has a functional “Start” <br/>Ability to enter Notes <br/>Must be able to navigate with arrow keys <br/>Color the notes/lines                                                                                                                                                                                                                                                                                                                         	|
| Immediate Issues/Questions?             	| TUI or CLI? <br/>↳ If CLI, what crate, how? <br/>↳ if TUI, what crate, how? <br/><br/>How will it play music? <br/>↳ How will it read that file? <br/>↳ Proprietary music files or std?    <br/>↳ Is there std sheet mus fmt? <br/><br/>Vim-like key binds? <br/>↳ oh yeah, how you gonna do key bind changes?                                                                                                                                                                                                             	|
| 5 Additional Features:                  	| Save/Load <br/>Pretty flyout menus with esc/caps canceling <br/>Configuration <br/>Plays Music back <br/>Mouse support                                                                                                                                                                                                                                                                                                                                                                       	|
| What’s Success?:                        	| All features added                                                                                                                                                                                                                                                                                                                                                                                                                                                       	|
| Any existing inspiration:               	| Musescore, guitar hero, pretty CLI apps like btop, or the Bubble Tea project for golang                                                                                                                                                                                                                                                                                                                                                                                  	|
| will it be maintained/updated? how?     	| N/A                                                                                                                                                                                                                                                                                                                                                                                                                                                                      	|
| Potential Updates?:                     	| GUI/Web version                                                                                                                                                                                                                                                                                                                                                                                                                                                          	|
