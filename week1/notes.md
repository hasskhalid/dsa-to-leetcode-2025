	Each week:
    git checkout -b weekX-topic
# Add code + notes
git add .
git commit -m "Week X – Completed <topic>"
git push -u origin weekX-topic

Merge back to main when done:
git checkout main
git merge weekX-topic
git push


