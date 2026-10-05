# Week 6 Assignment - Error Handling

This assignment practices using try/except to handle errors and keep programs running.

- safe_tools.py - Contains safe functions for division, number conversion, and dictionary field lookup.
- unbreakable.py - Reserved for the unbreakable input exercise required by the assignment.

An if check cannot catch abc by itself because abc is text, and the problem happens when Python tries to convert it to an integer. The int() conversion raises a ValueError, which must be handled with try/except.
