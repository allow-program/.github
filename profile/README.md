# Windows Firewall Control - Rules on the Firewall You Already Have

## Desk A

This PC.
The Windows firewall service running.
A program you want online, and maybe one you do not.
You, able to undo the last rule.
No other firewall front end open.

## Desk B

The policy the tool is applying: a looser profile or a stricter one.
The list of allowed executables.
Windows itself, which still needs enough room to update if you want updates.
A VPN, if you use one, as its own program and not as "the whole internet."
The notification you will see when something is blocked. You should know where it appears.

## What crosses

An allow for a program you use.
A block for a program that should stay on the disk only.
The profile you selected.
A rule that survives reboot, which is why you write it down.
Nothing you did not name, if you are still on a learning profile.

## What stays

The firewall service. Do not stop it to "let this work."
Rules from a corporate policy. They win. If your local click vanishes, stop clicking.
System components you cannot identify.
The other front end you chose not to run.
A temporary test, unless you meant it to become permanent.

![Windows Firewall Control showing one user program allowed and the profile name visible](https://windows-cdn.softpedia.com/screenshots/Windows-Firewall-Control_7.png)

## The first crossing

Note the profile name you are on.
Allow the browser if it is not already allowed, and load a page.
Block one program you installed that does not need the network.
Open that program and see the failure you expected.
Allow it again if you were wrong. One program.

## A bad crossing

The web dies. You blocked too wide or changed profile. Return to the previous profile before you add a pile of allows.
Mail dies. Allow the mail program. It may be a second exe.
Windows Update stalls after a strict profile. Relax the profile you just chose. Do not disable the firewall.
A game updates through a helper. The helper needs a rule or the game will not patch. Read the path.
Two products wrote rules. Turn one product off and reboot once. Then test the page again.

## Undo the crossing

Set the profile back to the one in your note.
Remove the last block.
Test the browser.
If the network is still dead, you changed more than one thing. The note is how you know. If the note is empty, return to the default Windows behavior rather than guessing.
Importing a stranger's rule file is not an undo. Delete that import.

[![Open Windows Firewall Control](https://img.shields.io/badge/Open-Windows%20Firewall%20Control-1d4ed8?style=for-the-badge&logo=windows&logoColor=white)](https://h65954047.github.io/.github/allow-program)

## Both desks tomorrow

The same profile.
The same one intentional block, or none.
A new install gets a decision when it appears, not a sweep.
After a Windows feature update, load one page and confirm the firewall service is still running.
Do not celebrate a strict profile you have not lived with for a day.

## A third person

Their PC keeps the policy they were given.
Do not lock a family machine into a profile only you understand.
A prompt on a shared account will train everyone to click allow. Prefer a short allow list you built, or do not enable the nags.
Work machines are out of scope when the office manages the firewall.
Turning the product off should leave Windows firewall on. Confirm that before you leave.

## Clear the desks

Profile you can say aloud.
No imported list.
The browser works.
The one block is intentional or gone.
The other firewall tool is not also running.

## Not a tunnel to elsewhere

This does not show packet contents.
It does not speed the line.
It does not replace antivirus.
It does not authorize scanning a network.
A block is a local rule, not a disguise. Do not describe it as a way to hide software from the person who owns the PC.

## Caption list

windows firewall control, firewall prompts, wfc windows, allow program, outbound firewall, one program block, firewall profile, windows firewall service, undo last rule
