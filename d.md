# Use Case: Create a science plan
**ID:** 1<br>
**Importance Level:** High<br>
**Primary Actor:** Astronomer<br>
**Use Case Type:** Detail, Essential<br>
**Brief Description:** Astronomer can create a science plan for observing astronomical data.<br>
**Trigger:** Astronomer want to create a new Science Plan.<br>
**Type:** External<br>
**Relationship:**<br>
- **Association:** Astronomer<br>
- **Include:** -
- **Extend:** -
- **Generalization:** -

**Normal Flow of Events:**<br>
1. Astronomer selects the "Create science plan" button.
2. The system shows the science creation plan page.
3. Astronomer input funding’s information.
4. Astronomer input objective’s information.
5. Astronomer input Stars system’s information.
6. Astronomers select date and time.
7. Astronomers select Telescope location.
8. Astronomer config processing requirements by
    1. Select file type.
    2. Select file quality
    3. Config image processing.
9. The system shows the summary of the information inputted
10. Astronomer can either confirm or re-edit the plan information

**Alternate/Exeptional Flow:**<br>
- If the input data is invalid:
    1. Show error message.
- If the creator wants to edit the detail of the plan before confirming the plan.
    1. Move user back to the edit page.
