# k8s-fastapi

## pipenv
```
❯ pipenv --python 3.9
Creating a virtualenv for this project...
Pipfile: /Users/volker/Dev/github/k8s-fastapi/Pipfile
Using /opt/homebrew/bin/python3.9 (3.9.13) to create virtualenv...
⠸ Creating virtual environment...created virtual environment CPython3.9.13.final.0-64 in 238ms
  creator CPython3Posix(dest=/Users/volker/.local/share/virtualenvs/k8s-fastapi-wO_mh93I, clear=False, no_vcs_ignore=False, global=False)
  seeder FromAppData(download=False, pip=bundle, setuptools=bundle, wheel=bundle, via=copy, app_data_dir=/Users/volker/Library/Application Support/virtualenv)
    added seed packages: pip==22.1.2, setuptools==62.5.0, wheel==0.37.1
  activators BashActivator,CShellActivator,FishActivator,NushellActivator,PowerShellActivator,PythonActivator

✔ Successfully created virtual environment!
Virtualenv location: /Users/volker/.local/share/virtualenvs/k8s-fastapi-wO_mh93I
Creating a Pipfile for this project..
```

```shell
❯ pipenv shell
Launching subshell in virtual environment...
 . /Users/volker/.local/share/virtualenvs/k8s-fastapi-wO_mh93I/bin/activate

[WARNING]: Console output during zsh initialization detected.

When using Powerlevel10k with instant prompt, console output during zsh
initialization may indicate issues.

You can:

  - Recommended: Change ~/.zshrc so that it does not perform console I/O
    after the instant prompt preamble. See the link below for details.

    * You will not see this error message again.
    * Zsh will start quickly and prompt will update smoothly.

  - Suppress this warning either by running p10k configure or by manually
    defining the following parameter:

      typeset -g POWERLEVEL9K_INSTANT_PROMPT=quiet

    * You will not see this error message again.
    * Zsh will start quickly but prompt will jump down after initialization.

  - Disable instant prompt either by running p10k configure or by manually
    defining the following parameter:

      typeset -g POWERLEVEL9K_INSTANT_PROMPT=off

    * You will not see this error message again.
    * Zsh will start slowly.

  - Do nothing.

    * You will see this error message every time you start zsh.
    * Zsh will start quickly but prompt will jump down after initialization.

For details, see:
https://github.com/romkatv/powerlevel10k/blob/master/README.md#instant-prompt

-- console output produced during zsh initialization follows --

Agent pid 11843
Identity added: /Users/volker/.ssh/id_rsa (/Users/volker/.ssh/id_rsa)
❯  . /Users/volker/.local/share/virtualenvs/k8s-fastapi-wO_mh93I/bin/activate

    ~/Dev/gi/k8s-fastapi    pipenv !1 ?1 



```
