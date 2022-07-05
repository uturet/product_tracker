# Amazon Product Tracker

### Project Shema

```mermaid
  graph TD;
    FrontEnd-->Backend;
    SocketIO-->FrontEnd;
    Product_Updater-->SocketIO;
    Backend-->SocketIO;
```
---
### Features
- Rich search system 
    - graphic interpretation of SQL
    - presaved requests
    - quick search

- Tags and colors for each tag

![SearchAndTags](SearchAndTags.GIF)
![QuickPresave](QuickPresave.GIF)

- SocketIO allows to push all the changes to clients immediately

- Users and permissions by roles

- Each user can configure product columns, and choose from presaved config

