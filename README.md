# SNServiceNotReadyForPortal

## Description

_This is a simple solution to allow a phased approach when converting the services to work on portal._

### Installation

- Import and commit the updateset found in [**dist**](/dist) folder.
- A new variable set called **Not Ready For Portal** is created along with a macro variable and it's related widget.
- If needed, run the fix script **Add Portal Message Variable Set** after updating the encoded query inside it's script to add the variable set.

### Usage

- Add the new variable set **Not Ready For Portal** to catalog that is not yet ready to work on portal.
- This makes catalog still access on portal but everything on the catalog form is hidden and a link is displayed to access the service in normal ServiceNow UI.
- The message that is displayed when the variable set is added to a service catalog appears as below.
  
![Menu](/doc/images/NotReady.png)

- The variable set can be added on catalog, record producer or order guide as needed.
- If the variable set needs to be added to a large number of services, make use of the fix script provided. Updates its encoded query as need and run it.
  
### License

GNU General Public License v3.0
