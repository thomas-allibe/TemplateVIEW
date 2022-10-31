# TemplateVIEW
A LabVIEW application template.

# ToDo
- [ ] Handle Dock / Undock
- [ ] Handle Title Bar / Side Menu Visibility
- [ ] Handle windows Icon
- [ ] Add Windows Icon Tray Support
- [ ] Handle Body Scrollbars visibility
- [ ] Keep Settings button in the generic UI ?
- [x] Give the Theme class UI References ?
  - NO -> there is only one instance of Theme class, it can have references of all UIs. Plus, some references could become invalid due to closed UI.
  - [ ] BUT -> there can be generic methods to apply theme on root items
- [ ] Add language file support
- Method Diagrams
- StatusBar Actor

# Window class
- Top Window:
  - Has TitleBar (Toggleable)
    - Has Title (togglable)
    - Has Close, Minimize & Maximize Buttons (Togglable)
  - Has native menu bar (Togglable)
  - No Docking / Undocking Feature
  - Has SideMenu (Toggleable)
  - Has StatusBar (Toggleable)
- Module Window:
  - Has TitleBar (Toggleable)
    - Has Title (togglable)
    - No Close, Minimize & Maximize Buttons when Docked
  - Has native menu bar (Togglable)
  - Has Docking / Undocking Feature
  - Has SideMenu (Toggleable)
  - Has StatusBar (Toggleable)
- Popup Window:
  - Has TitleBar (Toggleable)
    - No Close, Minimize & Maximize Buttons ?
  - Has native menu bar (Togglable)
  - No Docking / Undocking Feature
  - No SideMenu
  - No StatusBar
- Status Window:
  - No TitleBar
    - No Close, Minimize & Maximize Buttons
  - No native menu bar (Togglable)
  - No Docking / Undocking Feature
  - No SideMenu
  - No StatusBar
