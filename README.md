# Visual regression

This is a tool to do visual regression on toujou themes and content elements

Visual regression works by comparing a screenshot of the current state with a screenshot of a previous "approved" state.

Tools used:
- https://github.com/garris/BackstopJS


# Create reference images
This will create new reference images, against which future tests will be compared. [Docs](https://github.com/garris/BackstopJS#creating-reference-files)
- `npm npm refs`

# Test
Test the current state of your urls against the saved reference images.[Docs](https://github.com/garris/BackstopJS#generating-test-bitmaps)
- `npm run test`

# Approve
Update the reference images with the current state. [Docs](https://github.com/garris/BackstopJS#approving-changes)
- `npm run approve`
