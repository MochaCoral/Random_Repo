# Hi welcome
## here is where the fun begins - installing an IDE
---

So in order to log into a course-specific account on ieng6
first you have to set up your development environment, in which
case, I'm using VSCode. 

You can go ahead and ask jeeves where to find it on the world 
wide web, most likely hosted on the VSCode website 
> thanks microsoft 

steer your way towards installing it and setting it up for use with java by finding the extensions in the sidebar, you'll probably need things like testers like *JUnit* for posterity 
> can't escape the tests 

You can access your desired flavor of terminal right below by opening up a terminal straight from vscode - since I use Windows, *powershell* is used by default.
> rip cmd

From here, you could do most of the things you would want to do in a terminal, like navigating your computer's local directories, or compile and run java code **if you installed the proper vscode extensions**.
![VSCode](https://lh3.googleusercontent.com/MzE9NOOuO-S-4MHwdxHEBP_jJjFsPotrBa4ewJcHA44Iaqw41NDcJPoh1uV-2UAiyTHy8U33LCuKcHiEMvY2Eyi0SFpvUXxu8EZGanp510wMsF0arQr-KV8cadAVumeAXMZJjdGA0-ttjVuGljRhHa6xWNUANaQU74bwbrVEqWkzEZsAAIJ_TwBDNcKeQa2yljVGsR4Jp8zCmPX5YyOUTMlngTaGuxzrBWdSLfObOp1F0dwhFF-aUkLgQjSWMGNieMh_PABuGq1XC02gxKP7bgpgksMLBja-LcQU7i5kthqrE_PeLgZ9zdlSCqzwbXp05y8b5BQcC5eZoktknhK0IHd0Y09jY8k9loJ_5J7NHKz_vydFd3leKFNbd_aTu1fcfyEhjqh0WA7XmXSBF591ketWjoADHU7xsysXKnGxmEV2v0-8BtApo4NTKucooMZmuu2DVfOKzuFoaGbFX-XooDR_LfsqiB0tgzTdz0K3CXRre_tGJEdK3oVbTUXHPD5jnQTbNw_10kxcoKyohxAQ_IbvvkfABbXYi5OjNKNxX5wPRf3dqx3HUS1-Gp8EOHmT3NTTNH0Zf2lNXRBTlaTNfEl-q9DQOCJKGfyiNxupOsPQ85pm_Q8CrdF93SaGXqBq_e3fRaSFP49BQLbCPAbSFuLkTQwgsFfvp5X7k5M0jfbGBXecOWLIhesk7d-7-0T9_WGiBHwg2pnGUytgmUT53ZcoiQ=w987-h1315-no?authuser=0)


## Connecting to a Remote Shell :)
---
So now you've set up your own little slice of heaven on VSCode, you can now try to stretch your wings and fly through the cloud(s), by connecting to a remote shell. For the purposes of this tutorial, we will be using my own acount on ieng6. The key to this is the command:

`ssh <remote shell>` 

This lets you connect to a remote shell

Here's an example:

![Remoting](https://lh3.googleusercontent.com/6Qjs52E4kfKNJ_sWY1iHoQvAslIGv-PhZzwRVGA_-AYFX2kSh_6mPSXZ5bHi-gp7Q1PcJjN4Tlqvvz7oeoG-_HJ6kGRZWVEIE3IfU1Rn30636jQtTEX7Q4gixrFvXqMGnLGc6INip8ypPHqLF55UB0oe07j-SAl86rNUuqMJHxmgXCgnYxb51P7jChtyvwCfvA30IjaW9QWsCJQoSqt6Js0bJ7pTmF8Q05IN8c-2HEX04Kr3-Q4PKN23Zk2AiBMdSxxCD55TvS4sQI4qBnSH0bvTNxuqBigdBRN6UoYSbiobpRt24es4ngAl_f1ZHrMfg4jDytdCxOMpPSf3rkKsDNoiyxR4R71CUAMMAAjg-fg4M-D3BsBIcq3IiFp9hNOvxbmt6s0alEsZYdVH5CDpNMsvCsxATgHuYzloINuHMMIBzJW7yGOC-XdXlRzbx1yDtME2Lk9eDabCN6Q-yhQXH1gisxfhGkAwpmlC1pM3rjlT4vlsPsokUqsSSI_EV74R59oPvK9fawVtvU2iyevsYYAeU_5LOV2KSdh28POPwfYoqLLrDTKgYcbzLyQfWLLbadCI7lWDJuCSWQJR-hLRft1rvPlOqHhywRRtr4OEzXLiltpHr-V9lH0Qwz4FUAoRS8uObj_bO-ZZDv4VxlXxAJDxMS5h-kqoVELtju4lY5J6inqqZnJZQRCLo75qWpD3M8HeOiPP-yuWt2UoRygQd5OPZA=w656-h320-no?authuser=0)
> The first time you connect to a remote shell from a new local will prompt you with the text on lines 1-3, in which case, if you trust the remote shell, you can say `yes` 

You will then be prompted to input your password, which if you're a good person, you will have at your disposal *don't worry, no one will see it on the terminal while you're typing (just cover your keyboard while your doing it)*

Here you can do most of the things you could do on a local machine, except it's on a *c l o u d*. Which leads us very conveniently to the next portion, commands.

## Commands 
---
commands.

here's a list of a few important commands for those who've been navigating using a GUI based operating system for their whole lives:

- `ls` : this command lists whatever items are in the current working directory (when i say "directory", think "folder")
  - you can add other keywords after this command to enable other features of ls, like `-a`, which let's you see files that your directory is hiding from you, or `-lat` which let's you see a more detailed view of the items in your current directory
- `cat <file>` This shows you the contents of a file 
- `cd` stands for change directory, the main mode of transportation across the sea of black or blue or white depending on your terminal
  - `cd ..` sends you back to the directory above the one your currently in
  - `cd ~` takes you back to your home directory
  - otherwise `cd <directory name>` takes you down a subdirectory within the current working directory
- `pwd` prints out the current directory path

Here's a couple lovely examples of these commands in action via powershell:
![commands](https://lh3.googleusercontent.com/mZIYAOl7Ax0wy12q_QM3tE0kQC5QGvlAJbnI7aKbEIgkc3XJEKfK3N2XUg_E7eMpuDgNbh8RDY5RXEWP9NXuyXbEW5v9wxXwOWPZbC2NPHUsgMTZs1lbDTLuwqp0Ok9avufDyefgwo8sdvrSHAqULx8_9axb6gALfNOxObr_mLfvtmHciEZGOmMECS9cCuFYEXYDskqBhUgMzNfhoLX-DbAw7ocDBApmCyJlKkFoOUDtUKfjmwbEI4XIdP0KRCXVzNkv6srwcJ9Gv54OaPsjea4kgVy3zDsFT27P19n6gWY1CNOffGSsUju8LURlIMm490zFUAMo_2SZbgzT37-Ml9zcd9eMeu7GtsEPhGSglfZghE0xHQf88ESDNtDH_qsKNmVTdSQ54SvmJGrf29PJ1ZGd5DrDOrda_IQalSytvw0FbzrmOF8N8WRJ_6KRsZoLNG68iBrGVCLpdKp7RpD_4XklUX7-JQ3SCBPAn3Dm0XTBjXTlR-08qr3VH8H1a-BqDda7pQbs5sLxX2JsShVUDZDBqn9uYFG_GsZruGXEFj5Nci0uRi9AvNnqOxR1mk0JFMLTUwMZsA0WyruQzf0odD9lSRNH-FEXgwyc9Ch8FcTHDA3fxROKZoPi83Eeb1M43WwREEjQMaZdoqkkA_IeDbMMN0BjWQh7yLz5AqsgYpGXqWmudMznJl4wOZnlFEsmlI_c1qn3VtWnxuMBvfn3n0SSaA=w574-h449-no?authuser=0)
> Here I'm performing the terminal equivalent of a lap in my remote directory 

the next command is is of particular importance for a multitude of reasons 
- `cp <file> source  destination` allows you to copy a file from one directory to another 
  - an important thing to note is that when you copy a file to a directory containing a file with an identical name, it will overwrite the contents of the file in the destination.

this is useful for all your file organization needs. what really gets exciting is the other form of this command
## Moving Files with scp
---
- `scp <file> [source shell] [destination shell]` standing for secure copy, scp allows you to copy files or directories between different shells 
![secure copy](https://lh3.googleusercontent.com/8gMsuoothV5qxz-0SCq8OM7vakvDfnnQUw2VnDk8yk-etS6tDvfAEuiaI_K078OZE2PMP8vnbqoumOPfGSEdHnsfUWMKpwEvq9m_wOXrW-svucdgKFxCrX6rwdl4neVp8tTSjT_F6vN_NiKG6NBqGqVNoHpa4vMv5y9lUw4Olu9YsnNrlmVHJLzvh11ro-SMBTyPbimAuIAA23fpl0E8UmfRv7Ju_6brnXP0nwyzPQw13m4feAnkywPwGWkGXIcLFzFt_6GY_eUhh6o5rpZr_8_EXrT5Nx8ghtPNT7-jcfoMPaBTV4qKmlJSIBpKu6UdAhZ9nDAOHLBmOHepjNmPBGt5PEpPX1sFKC9HrB3SdqFM5mQjlt4x13sJsHYShNUNZ3dYRnNBgz78yhXR2Ljv-ZdHxFN0jiTgFE4rGCmZkpuzqOMnBcTa673LewFoIChWr6GhB-WdWfakPvwmkEo1tEVtG6E6d6W5e_XhkwnnrnkgYf-IksTutgzGNAhpJHIW29j8grXMlS1L_prPP2yzNHe2aSOuOSeccCxvLQ3Ri8vh5ClR2ZrGXYoEjiSyRLtIeKlEqwjf5GOq_QNySNMmcSo5dFzgTwYRXMN8wd6_iYDHAbAJ8xeFQTFkGu9U71WBuUMN1KcaV-O2eyKx2VkKCMSPHmuXFM-FHCIcpUfYe8qm3vZTv2oPEeueNeYzJagBDCw-9KUN_O50FPlhNFLhXBL22A=w838-h601-no?authuser=0)
> here you can see that I've copied a file `Example-file.java` from my local machine to the remote directory (*note that i ommited the [source shell] from the command, which defaulted the secure copy from my current working directory*)

This will be important with regards to the next topic, which is setting up an ssh key

## That Sweet [[keygen]]
---
if you want to navigate between your local machine and a remote shell like a pro, you'll need an ssh key to help streamline your `ssh`s and your `scp`s. An ssh key involves a pair of keys that are created to mate your machine to the remote shell in holy matrimony. These two keys create a link that cannot be broken (unless you delete one of them), acting as a alternate means of authenticating your machine's access to the remote shell.

the first step of creating this link is to generate the key pair for your particular machine using the command `ssh-keygen`, materialized in a new hidden folder in your home directory called `/.ssh`. Here you will find two keys, a public key with the extension `.pub` and another private key with no extension. keep the private key private, treat it like a password (For windows users in particular, follow the documentation regarding **ssh-add** over [here](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement#user-key-generation)).

what you want to do is copy the private key from your local machin to the home directory of the remote shell. This should complete the link between your machine and the shell, making for seamless navigation and moving between the two.
![keygen](https://lh3.googleusercontent.com/OT-i5QyxkXZHScMaF4KzH3rOWeHtmUmmly6N7TzoF2C88C8Ia0x7Z6UY6Ta9go2HMa0_LH-LWaSiOIjurPFisKja3_8gO31Jx9eQFn-cvZx_9jclzxjDSpwr2dDiKR6kH4D3eCAJI1xBBoRfsQl8mKIrFuPpMOZXXi2aC9YNxI8SdAG2jkVrdpWxK0XwIbkYLiE3DIrA6PaUfuVqqvmgDJQTaJqtj2UAO_EyN41nXwpxLoTva9RTyC9MUIMRFkilOdYM21x1431giVs5yMgsu21oVEvFBkOOXQoCy32PZTZbmRovdra-9GHKHdaSFGO-aK-yEDQnuktS0LbQCe02gW-MyjmpzZvgWs6TZqTTXEjxOclcx-hOObGxjIW8vCCrkJ3k3BRho87ElPPsx5rj79_TwHl_LREBUZgAZAOE6YfxmXbQgX9kGww-BKPhV6CCLMJLDyJRKaVzjRWZvspVlOqKjO-ijPz79LdiH0NvFFXTREV0QBoTpTusqhEbp2MMCazfpNevwKJhFOz9MIp5dEOMTm7KYAA82vKTgNjohFby1lFj47hTM-ByYBuhkvHhdbU_mi6erckVLH12OhRBlIG_iTMq7LII1ZhyL-ODFcF2pENwE5jP4nScQvqv-nNRmGcUb7pOf53yPIfektfg9kQhR3vKzzriiFZnH3c8o8_sTLolEQCwv9oGaNAStml8hXE_HidAdCplchB2nyQntWHHDQ=w834-h280-no?authuser=0)
> In this image I've created the key pair using the command `ssh-keygen`, it will first ask you to enter the file and path to save the key, then it will ask for an optional passphrase 

![key pair](https://lh3.googleusercontent.com/8Et1voG_67hC-dOwt4Ra5NQ-Rn0uCYPns6s0-y3QlvdeWzEcEqG6VYE_s37Gln6O0fi1_xDuVwonjHf9pI7Ubyt88_SNl1SauGSHsczXxubLjTPgpFnz-4h2CJ6VaKHHiKJpnJQvNlIf_AHoCIKCUdEbljf4XXKTdhJgVpGlrHDNiNYayo4FvLTQhNr6sBxZ6t0YLOIUuTBohCtGRgSfDO_clWExwnLg1FQ49pFxxWin6vGhcomF8O14EIVzgWFuDyHeastV8jhBf1LUpE-F9nYfV9tkN4vde23aGjcIH8N_hxxhx0XDTP7ZpJc8F1pOiqvzcriZgz6QpdotXvm7NFKE5Rg4M0GYTbEFRSgfrhdvaBjWYdGX9B8pDv3gIq50dTHcbJ1hOWG_1hXdgcuJWwypcYEVWyYL_rl7WeM7MCbOFFy3nCy-hNN0pBrvke0Gzj3BFBTc2BSCSuadSEd9VwfSiKPu2m0DrlV4Q2MaJjtxEQ26BqCe01VsQ2VEypZwMbbIoFfUD7EbwNwQQpvxwXKiQ_rMV85AW8wxRVAIgNh7A9JJr_6ZJe1WXhW6xYyibli1nTAnYDAFny-t4gPsm5MOx2gbcgdubhgpgdigJID3kYfysnSZvDhb3ZjYC-hjPLk3memrtNkZ38OSAuGW4Z8Y0rUW4gsrV5LYOWpMBnVwtaT3e7_Njs60Nbg72tqlRteBQ2wh7j5GvU-Jr2143Il9tA=w801-h220-no?authuser=0)
> This image shows the directory where the pair of keys have been saved, keep an eye the one without an extension 

Once you have done this, you can use `scp` to shoot your key through the tubes of the internet to your desired shell (remember to create the directory `~/.ssh/authorized_keys` in your remote shell, that is the desired destination for the key using the command `mkdir`)

From there onwards, you can access your remote shell with ease.

## A few more things for making ssh more pleasant
---
- you can run commands directly to the remote shell via the `ssh` you've been using before, as in:

`ssh cs15lwi22@ieng6.ucsd.edu "mkdir new-dir"`
- you can also perform multiple commands in a single line by using semicolons, like:

`cd ..; javac Example-file.java; java Example-file.java`