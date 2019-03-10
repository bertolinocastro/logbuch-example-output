# logbuch-example-output
An example of [Logbuch](https://github.com/bertolinocastro/logbuch) outputs and hidden data. Please, check it out.

Each folder inside this repository is an output folder defined in `projects_folder` parameter at configuration file.

Each example folder follows the '-l' option structure as follows:
```
 demonstration┐
              │
              └──────── * Default ┬───── A 2nd subject
                                  ├───── A 3rd subject
                                  └───── A newly created subject
```
```
 example-pandoc-markdown┐
                        │
                        ├──────── * A repeated project ───── A copy from other subject
                        └────────   Dummy project ───── Quick markdown example
```

Each folder has a `.git` inside it, as result of git integration with `Logbuch`. The usage of this integration is not mandatory, but recommended.

___In order to publish this repository with subrepositories, I renamed the `.git` folder to `.git_` in each of them. So if you want to completely check this example repository, rename these git folders back to `.git`.___
