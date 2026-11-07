# RSBUbash
Really Simple but Useful Bash is a small script that adds some nice Bash aliases to your .bashrc.
## Installation
Installation is quite simple. Just run this command in your terminal:
```bash
curl -s https://raw.githubusercontent.com/Ironbill25/RSBUbash/refs/heads/main/rsbubash -o ~/.rsbubash && echo -e "\n# Include RSBUbash\nif [ -f \"\$HOME/.rsbubash\" ]; then . \"\$HOME/.rsbubash\"; fi" >> ~/.bashrc && source ~/.bashrc
```