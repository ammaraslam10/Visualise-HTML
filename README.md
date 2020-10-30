# Visualise HTML

Inspired by [Jesse Ruderman](http://www.squarefree.com/){:target="_blank"}'s [Real-time HTML Editor](http://htmledit.squarefree.com){:target="_blank"}

This implementation fixes a few issues and adds a few features. It uses a single frame. The frame itself is created on every rewrite to fix the JS issues.
* JavaScript code modifications will now produce intended output. Fixed function/variable "ghosting" 
* A localStorage backup of the text is created after every 3 seconds, accidental refereshes are not a problem anymore.
* Moved to a vertical layout
* Support for tabs added
* Resized frame position is also kept intact through localStorage
