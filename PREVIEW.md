# Preview and test

Once Netlify finishes processing this update, open the preview link supplied with the update. Refresh the page to see the new photos.

For a local preview, run this command from the project folder with Netlify CLI installed:

```sh
netlify dev --port 8889
```

Open http://localhost:8889. This is a static site, so you can also open `index.html` directly in a browser for a quick visual check.

1. Inspect the hero and all 10 cards on desktop and at mobile widths such as 375px and 390px. Check that the subjects look sharp and the crops fit their frames.
2. Select one answer in each of the five questions. The selected card should show a gold border and checkmark. Selecting another card in the same question should replace the selection.
3. Try submitting with missing answers or required fields. Complete the answers, use dummy contact details, and tick the required consent checkbox to test the success message.
4. Scroll through all five questions and confirm that every stock photo appears. The hero and ten card photos are embedded directly in the page, so the preview does not depend on separate JPG requests.

The form remains a demo. Its success message does not mean an entry was stored or sent.

Photo source links are recorded in `PHOTO-SOURCES.md`.
