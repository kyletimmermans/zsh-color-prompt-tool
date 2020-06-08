Reference: https://stackoverflow.com/questions/35281630/how-do-i-change-my-ps1-on-a-macbook-for-oh-my-zsh
           <div>https://scriptingosx.com/2019/07/moving-to-zsh-06-customizing-the-zsh-prompt/</div>
           <div>http://www.nparikh.org/unix/prompt.php (all zsh prompt symbols)</div>
           <div>https://github.com/mayankk2308/set-egpu/blob/master/set-eGPU.sh (eleveate privileges)</div>
           <div>https://stackoverflow.com/questions/9268836/zsh-change-prompt-input-color (simple export prompt)

Steps:
1. Print Welcome Message
2. Elevate privileges, if not given correct permissions, print error
3. Show list of parts of prompt
4. Let them chose which parts they want and hit done
5. Now Print list of colors for reference
6. Allow them to chose each piece of their PROMPT and color it
7. Place export PROMPT='their choices' into ~/.zshrc
8. source ~/.zshrc
9. echo "Changes Saved"
10. exit

<div>-For install: Make curl that auto runs, auto chmod +x, autodeletes itself</div>

<p> Esentially creating nice one line string with user preferences from pretty menu that will be exported to ./zshrc </p>

</br>

## Also check built in colors for zsh

<p align="center">
  <img src="https://github.com/kyletimmermans/zsh-color-prompt-tool/blob/master/resources/color-list.png?raw=true" alt="Color List"/>
</p>
