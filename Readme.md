#### Develop locally
- If you prefer to develop locally, simply follow the steps below

#### Environment set up steps
1. Create a new Python virtual environment to safely install the SDK packages:

- On MacOS and Linux run:

   ``` bash
   python3 -m venv .venv
   ```

   ``` bash
   source .venv/bin/activate
   ```

- On Windows run: 

   ``` bash
   python3 -m venv .venv
   ```

   ``` bash
   .venv\scripts\activate
   ```
   deactivate the virtual env once done with the project
      ``` bash
   .venv\scripts\deactivate
   ```
2. Now that your virtual environment is activated, install the SDK packages
    #- First, navigate to the src directory. This is where you will do the majority of your work.

    ```bash
    #cd src
    ```

    - Next, install the requirements in your venv. Note: this may take several minutes the first time you install.

    ``` bash
    pip install -r requirements.txt
    ```
3. If you haven't already done so, run `az login` to authenticate to Azure in your terminal.
    - Note: if you are running from within a Codespace or the curated VS Code cloud container, you will need to use `az login --use-device-code`