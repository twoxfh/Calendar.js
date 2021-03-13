## Welcome

This page is under construction, so please be patient! The development of Calendar.js is ongoing and new versions are being pushed regularly, so keep checking back!

![CalendarJs](https://saunterjs.co.uk/images/calendarjs.png)

Calendar.js includes the following features:

- Adding, updating, and removing events, with full custom colors support.
- Full API available via public functions.
- Drag and Drop for events.
- Configurable text for translations.
- Day, Week, Month, and All Events views.
- Fully styled in CSS/SASS (including the buttons).
- Custom events for actions (adding/updating/removing events, skipping months, etc).
- Export to CSV, XML, JSON and TEXT.
- Full-screen mode (double clicking the title bar).
- Search support.
- Repeat every Day, Week, Month, or Year (with exclusion days support).
- Customizable holidays.
- Navigation keys (when full-screen mode is activated):
  1. Left:  Moves to the previous month.
  2. Right:  Moves to the next month.
  3. Escape:  Closes full-screen mode.
  4. Down:  Jumps to the current month.
  6. F5:  Refreshes the current view.
  7. Ctrl/Command + F:  Opens the search dialog.
  8. Ctrl/Command + Left:  Moves to the previous year.
  9. Ctrl/Command + Right:  Moves to the next year.
<br>

## Recent Changes:

So see all the latest changes, click [here](changes.md).
<br>
<br>

## Options:

So see all the available options, click [here](options.md).
<br>
<br>

## Event Object Format:

So see how an event object should be formatted, click [here](event.md).
<br>
<br>

## Holiday Object Format:

So see how an holiday object should be formatted, click [here](holiday.md).
<br>
<br>

## Getting Started

You will need to include the JavaScript file and CSS Style Sheet in the head of your HTML:

```markdown
<link rel="stylesheet" href="src/calendarjs.css" />
<script src="src/calendarjs.js"></script>
```

You will also need to set the page character encoding to UTF-8. This can be included in the head of your HTML as follows:

```markdown
<meta charset="utf-8" />
```
<br>

## Creating a container DIV

Add a div into your HTML and assign it an ID, as follows:

```markdown
<div id="calendar"></div>
```
<br>

## Initialising Calendar.Js:

It's now time to initialize Calendar.js, which is done as follows:

```markdown
<script> 
  var instance = calendarJs("calendar"); 
</script>
```

After this, the calendar will be rendered and you will have access to the public methods available.
<br>
<br>

## Finishing Up:

That's it! Nice and simple. Please refer to the code if you need more help (fully documented).

Minimized versions of the files are available.