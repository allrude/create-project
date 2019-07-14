# Create Project

Create project is a bash script
that runs the setup needed for each project type.

From a simple Vue project to a complex Magento project.

## Installation

Run the `install.sh` script via curl.

```bash
bash -c "$(curl -LsS https://raw.githubusercontent.com/GrimLink/create-project/master/install.sh)"
```

This will download and copy the files to your target folder.

## How to

Run `create-project` to start the installer

Create-project will always ask for the folder location and project type, if they are not added as paramters.

To run it with paramters

```bash
create-project test magento
```

After this the installer task will do it's thing.

_Complexer tasks will ask for more information._

## Notes and FAQ

Create-project assumes that you have an gitconfig
with the name and email added to you user.

Else create-project will leave these default values empty.
Which could cause an issue.
If you also leave them empty when creating an project.

## TODO

- [x] add update task
- [ ] add version to see if you running the latest