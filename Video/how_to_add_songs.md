# How to Add Songs to ProPresenter with a CCLI Number

This guide outlines the step-by-step process for adding songs to ProPresenter using incorporating CCLI numbers for simplicity. The process integrates with Planning Center Services, to source song details and ensure accuracy. We'll cover obtaining the CCLI number from Planning Center, verifying it against uploaded chord charts, importing the song, and performing reflow editing with specific custom groups.

## Step 1: Obtain the CCLI Number from Planning Center Services

Planning Center Services maintains a song library with detailed metadata, including CCLI numbers, making it an efficient source for accurate song information.

1. Log in to your Planning Center account and navigate to **Services** > **Songs**.
2. Search for the desired song by title, artist, or keywords in the song library.
3. Select the song to view its details. The CCLI number should be listed under the song's metadata (e.g., in the "Copyright" or "CCLI" section).
4. If the song doesn't have a CCLI #, you can navigate to one of the song's pdf files in the arrangements and find a CCLI # in the chord charts details at the bottom. 
5. If the song isn't in your library yet:
   - Click **Add Song** or use the import feature.
   - Search via integrated CCLI SongSelect within Planning Center (if enabled) by entering the song title or CCLI number directly.
   - Alternatively, import from external sources like Chord Charts or MultiTracks, which often include CCLI data.
6. Note down the CCLI number, song title, authors, and lyrics for later use. You can also generate a CCLI report from Planning Center for bulk verification: Go to **Songs > Reports > CCLI Copy Report** to export song details including CCLI numbers.

This step ensures you're pulling licensed, up-to-date information directly from your planning tool.

## Step 2: Verify the CCLI Number Against the Uploaded Chord Chart

To maintain accuracy and avoid copyright issues, cross-check the CCLI number from Planning Center with any chord charts you're uploading (e.g., PDFs from resources like PraiseCharts or MultiTracks).

1. Upload or open the chord chart file for the song (e.g., in a PDF viewer or ProPresenter's import tool).
2. Locate the CCLI number on the chord chart—it's typically printed at the bottom of the first page or in the footer, formatted as "CCLI # [number]".
3. Compare it directly with the CCLI number obtained from Planning Center in Step 1.
   - If they match: Proceed to the next step.
   - If they don't match: Investigate the discrepancy. The chord chart might be from an outdated source or a different arrangement. Update the song in Planning Center with the correct CCLI number via SongSelect integration, or contact your CCLI administrator. Do not proceed without resolution to ensure compliance.
4. If using Planning Center's import for chord charts, verify during the upload process that the metadata (including CCLI) aligns.

This verification step prevents errors in reporting and ensures all displayed content is properly licensed.

## Step 3: Import the Song into ProPresenter

With the verified CCLI number, import the song into ProPresenter. This can be done via direct SongSelect integration or by syncing from Planning Center.

### Direct Import via CCLI SongSelect

1. In ProPresenter, go to **File > Import > SongSelect** (or press Cmd+F and search).
2. Enter the verified CCLI number in the search field.
3. Select the matching song from the results. ProPresenter will import lyrics, chords (if available), and the CCLI number automatically.
4. Save the song to your library. If syncing with Planning Center, the imported song will now link back for future services.

## Step 4: Perform Reflow Editing and Add Custom Groups

Reflow editing in ProPresenter allows you to reorganize song slides quickly for better flow during worship. During this process, incorporate two new custom groups: 'Intro' and 'Blank'. The 'Intro' group will display the song title manually added for visual emphasis.

1. Open the imported song in ProPresenter's editor: Right-click the song in the library > **Edit Presentation**.
2. Select the Reflow Editor toolbar button. This opens the Reflow Editor, where you can drag and drop text blocks to create slides.
3. In the Reflow Editor:
   - Identify or create sections based on the song structure (e.g., Verse 1, Chorus).
   - Add a new group for 'Intro':
     - Click the **+** button to add a new group.
     - Name it 'Intro'.
     - Manually add the song title as the content (e.g., type or paste the title from Planning Center). Format it boldly or with a theme for prominence. This slide will appear at the start to introduce the song.
   - Add another new group for 'Blank':
     - Click the **+** button again.
     - Name it 'Blank'.
     - Leave it empty or add a simple blank slide (no text) for transitions, cues, or instrumental sections. This is useful for breathing room during performances.
4. Rearrange groups as needed: Drag 'Intro' to the beginning, followed by verses, choruses, etc., and place 'Blank' where pauses are required.
5. Use the Arrangement Editor (accessible via **View > Show Arrangement Editor**) to save multiple versions of the song layout without duplicating files. For example, create an "Full Band" arrangement with all groups.
6. Preview the song by clicking **Play** to ensure smooth transitions. Adjust slide timings or transitions if necessary.
7. Save changes: Click **Done** to update the presentation in your library.

These custom groups enhance organization and professionalism, especially for live worship flows.

## Step 5: Add and Display CCLI Information

To comply with licensing, display the CCLI number on slides.

1. In the song editor, go to the last slide (or a dedicated copyright slide).
2. Add a text box with the verified CCLI number, song title, authors, and your church's CCLI license number. Format: "Song Title | Authors | CCLI # [number] | © Church Name License # [your license]".
3. For automation: In **Preferences > Display**, enable CCLI info to auto-populate on slides.
4. If using themes, create a "Copyright" theme to standardize this across songs.

## Final Tips

- Test the full song in a rehearsal mode to verify flow, including the new 'Intro' and 'Blank' groups.
- For bulk updates (e.g., converting existing songs to include CCLI), use ProPresenter's library search and edit multiple items at once.
- Regularly sync Planning Center services to keep ProPresenter updated.
- If issues arise (e.g., import failures), check ProPresenter's support resources or Planning Center's integration settings.

By following this process, you'll ensure songs are added accurately, legally, and optimized for your worship team. For video tutorials, search for "ProPresenter SongSelect" or "Planning Center ProPresenter Integration" on YouTube.
