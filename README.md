# Visual regression

This is a tool to do visual regression on toujou theme

Visual regression works by comparing a screenshot of the current state with a screenshot of a previous "correct" state.

Tools used:
- https://github.com/garris/BackstopJS


# Create reference images
This will create new reference images, agains which future tests will be compared to. [Docs](https://github.com/garris/BackstopJS#creating-reference-files)
- `npm npm refs`

# Test
Test the current state of your urls against the saved reference images.[Docs](https://github.com/garris/BackstopJS#generating-test-bitmaps)
- `npm run test`

# Approve
Update the reference images with the current state. [Docs](https://github.com/garris/BackstopJS#approving-changes)
- `npm run approve`