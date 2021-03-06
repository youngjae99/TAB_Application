# TAB_Application

This is a repository for development of application with tabs  as coursework in MADCAMP, 2020 SUMMER, KAIST. 

### TAB1

> LIST of Contacts

* Recycler View, Json, Itemtouchhelper (swiping & dragging to change the order function): Using the json file we construts the contacts list. In the tab we can add the new contact with name and phone number. With swiping the item, we can erase the contact from the screen. With drag and drop, we can change the order of the contacts. By long clicking the contact, the screen will be moved to dial screen.

### TAB2

> Gallery

* Grid View, Glide Library, Photo View (from git): Basically we used the grid view to show the photos from the mobile's gallery. To take all of them we apply the cursor from the managedquery. Glide library helped to speed up the uploading images. On the single image show screen, with the github library (link: com.github.chrisbanes:PhotoView:2.1.3), we can zoom in the image. And using the prefer button, can change the selected specific images or all images list.


### TAB3

> Calendar

* Calendar view, Recycler view: With the android's calendar view, we can get them on the tab3. To add the schedules on the specific day, we used recycler view to show the schedules we added by clicking the button at the bottom. 


## Development

### Branching Rules
examples : 
```
$ project1, project2, ..
$ feature/<name>/project1
$ feature/<assignment>/<method>
```
### Commit Message Format
```
<type>(<scope>): <subject>
```
#### Type
Should be one of the following:

* **docs**: Documentation only changes
* **feat**: A new feature
* **fix**: A bug fix
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* **misc**: Adding miscellaneous items

#### Scope
Changed file name or none. 

#### Subject
The subject contains a succinct description of the change:

* use the **imperative, present tense**: "change" not "changed" nor "changes"
* **do capitalize** the first letter
* no dot (.) at the end

## Collaborators

* [Hong Seok, Kang](https://github.com/ghdtjr)
* [Eun Jin, Heo](https://github.com/eunjinheohy)

