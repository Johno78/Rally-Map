# Rally Test Map Maker

Draws Targa-style rally test maps over a real map, with the route, direction arrows, cone diagrams (with Pass 1/Pass 2 splits), code boards and S/T/F markers. Prints to an A4 PDF.

Live: https://johno78.github.io/rally-map/

- **Event**: holds every test of a rally. Add, duplicate and reorder tests, then **Print whole event** for the full test book.
- **Distance and bogey**: worked out automatically from the *Test route* lines, at the event's bogey speed (default 30 mph).
- **Code boards**: each board stores its code, which is checked against the 5/7-character rule and for duplicates. **Marshal mode** shows the codes on the map and adds a table with OS grid refs.
- **Pass 1 / Pass 2**: any item can be set to show on one pass only. You can view each pass on its own and print a page per pass.
- **Save event file** downloads a `.json` file. Use **Open event file** to load it again.
- When printing, set margins to **None** and turn on **Background graphics**.
