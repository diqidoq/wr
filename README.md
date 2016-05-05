About
-----

The terminal command `wr` is a utility to manage distraction free writing in terminal.

This terminal utility will help and simplify the start up process for writing in a nice terminal mode and saves the work distraction free under given date/time/type. This is useful for out of the way notes without manipuating the user settings for terminal or terminal text editors as a whole. It will also include upcoming features to switch edit tools and outlining in the future.

© 2016 | author: Digidog (aka. diqidoq), in courtesy of maroqqo.com. This program is free software released under the GPL v3 License.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

Init
----
On first run of wr it will ask you to provide a default SOURCE / TARGET path.

 + ERROR: `<directory>` seems not to be where it was expected, or it is not mounted.
 + SOLUTION: Make sure that the paths of your provided SOURCE and TARGET directories really exist. Some usb devices have other mount points in your system than you would expect. Test your expected mount paths if this error occures.

Commands
--------
    wr                 starts wr for fastly start writing (only asks about type of document)
    wr -h | --help     prints help
    wr -d              reconfigures SOURCE and TARGET path
    wr -n | --name     will start wr with given document (choose dialoque)
