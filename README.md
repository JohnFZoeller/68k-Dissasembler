# 68k-Dissasembler

Personal Project

This WAS a final project in my hardware class at the University of Washington Bothell, (CSS 422 Hardware and Memory Organization) 
but I enjoyed writing my portion (and then some) so much that I decided to make this a personal project. 

GOALS
-edit and polish
-eliminate bugs
-replace blakes version of I/O with my own
-add support for my opcodes. 

CREDITS
-Full Credit goes to Blake Hashimoto for writing the input output file (Main.x68), and about 80% of the driver file. 
-Also to Kristen Attebury for writing the original OP_jumptable.x68.
-I editted the OPCode portion extensivley, not to suggest my collegue didn't work hard... 
  but as it stands, I think its fair for me to claim 50% credit for OP_Jumptable.x68.
-I wrote 100% of the EFFECTIVE_ADDRESSES.X68, and testingFile.x68.
-the change log catalogs all of the changes I made in the last 48 hours before the project was due. 

INITIAL BUGS REPORT (6/27/16)
-movem has multiple bugs... its mostly functional but there are too many to list. 
-sub seemed to cause quite a few errors in the final version. 
