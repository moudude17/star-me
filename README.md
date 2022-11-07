# :star2: Star-me amFOSS

#### Starring is fun! 

#### The script in this repository connects developers automatically with FOSS@Amrita projects on GitHub. You just need to run this script.



# :ledger: Steps

## 1. Sign In

Make sure that you are signed up in your *GitHub* account on the default browser, if not do so now !

<!-- add any reference where they could installed git and all-->

## 2. Installing `gh`

### Debian & Ubuntu:

Resynchronize the package index files :
```bash
sudo apt update
```

Install gh :
```bash
sudo apt install gh

```
If sudo doesn't work for you, try using this command:
```
snap install gh
```

### macOS:

`gh` is available via Homebrew.

**Make sure that you have Homebrew installed in your mac to install the below step 👇**

Installing through Homebrew :
```bash
brew install gh
```

**Note:** MacOS users may also need to install [wget](https://formulae.brew.sh/formula/wget), if not already present.

### Other Linux distributions:
For more details check [Link](https://github.com/cli/cli/blob/trunk/docs/install_linux.md).

## 3. Setup:

**Make sure that you have installed `gh` successfully in your pc before starting this step**

```bash
gh auth login 
```
#### Below are some of things which show up when the above code is entered.

- `What account do you want to log into?` - GitHub.com (use your up and down keys and `enter`)

- `What is your preferred protocol for Git operations?` - HTTPS

- `Authenticate Git with your GitHub credentials?` - Yes

- `How would you like to authenticate GitHub CLI?` - Login with a web browser

**There will a one-time code which will be shown (example:xxxx-xxxx), copy the one-time code and `enter`**

Paste the one-time code in the browser page which is opened and authorize.

<!-- ![](./assets/1.png) -->
<img src = "./assets/1.png" height="400px" alt="GitHub Auth Done Screenshot">


Once the verificaiton is done you are all set to go : 

**Make sure that the username of your GitHub is correctly displayed in the terminal.
`Logged in as <your-username>`**

## 4. Run the Python script!

```bash
wget -O script.py https://raw.githubusercontent.com/amfoss/star-me/master/script.py && python3 ./script.py
```
## 5. Wait until the script is finished

The script needs to run for a while. At the end it will display "Starring Done". Ensure that it runs until the end.

<img src = "./assets/0.png" height="400px" alt="starring done Screenshot">
