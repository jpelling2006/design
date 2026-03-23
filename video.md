# demonstration

1. **mention that the user has outlook open succesfully and that only "inside my organisation" is considered**
2. **home state**
   1. **show that many replies can be defined**, viewed, edited, and deleted
   2. view state
      1. show edit and delete buttons (ease of access)
      2. boosts flexibility of use and user convinience, so users dont have to keep on switching back and forth
   3. delete state
      1. exists for error prevention purposes, allows the user to realise theyve made a mistake before committing to deletion.
      2. avoids accidents and guides the user through the decision making process
      3. confirmation dialog is designed to prompt a simple 'Yes/No' decision, making it clear that deletion is irreversible
3. **create state**
   1. explain this is also the edit state, but the edit state would have information pre-filled based on prior configurations
   2. **show that you can**
      1. **set date range**
      2. **set time range**
      3. **set specific days of the week**
      4. change text formatting (font, size, bold, italic, etc) quickly, emphasising ease of use
      5. users can fine-tune their messages to match their exact needs, which improves control and flexibility
   3. **mention the text is there as dummy data**

# explanation

- **usability guidelines**
  - **consistency**
    - by using common design patterns like save, cancel, and edit buttons, the interface remains intuitive. 
    - this consistency reduces the user's cognitive load and enhances usability since users don't need to relearn actions
    - consistent placement of action buttons and form fields help users predict where to find important controls
  - **error prevention**
    - delete state is important since is boosts error prevention and users are asked to confirm the irreversible action of deleting a message
    - this follows nielsen's usability heuristics for preventing errors
  - **user control**
    - users can cancel their actions at any point in the interface, providing them with control and reassurance.
    - confirmation dialogues (are you sure you want to delete this message) prevent accidental actions
  - **feedback**
    - feedback is provided through status messages ("you have 2 messages")
    - toggle changing from enabled/disabled depending on the status of toggle
    - confirmation dialogs
    - feedback elements allow users to know what's happening at all times

- **design patterns**
  - **modals**
    - modals are used for view/delete states since they are common in application design.
    - they avoid unnecessary page reloads or navigation
    - they focus the user's attention and helps them make decisions w/o navigating away
  - **switches**
    - toggles are familiar interface patterns that help users quickly understand settings
    - they imitate a real life light switch, indicating that a feature can be turned on and off
    - when a switch is on, its highlighted in blue for clarity

- **visual and info layout**
  - **colours**
    - blue for primary actions to make them stand out whilst being a neutral colour
    - red for destructive actions follows common colour conventions in interface design, signalling danger
    - green for creation aligns w them too, signalling positive or new actions
    - gray and white are used for secondary actions, minimising visual clutter and focusing attention on key actions
  - **info grouping**
    - grouped fields (date/time controls) makes info easy to digest and follow, as grouping similar actions enhances information processing
    - meets usability standards such as fitt's law for ease of use and visual hierarchy

- **error prevention / detection**
  - delete confirmation page prevents irreversible actions. 
  - critical for error detection and prevention
  - users are warned that its irreversable