<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE score-partwise PUBLIC
    "-//Recordare//DTD MusicXML 3.1 Partwise//EN"
    "http://www.musicxml.org/dtds/partwise.dtd">
<score-partwise version="3.1">
  <work>
    <work-title>Verse1_UserBlueprint</work-title>
  </work>
  <identification>
    <creator type="composer">User-specified blueprint</creator>
    <encoding>
      <software>ChatGPT MusicXML Generator</software>
      <encoding-date>2025-12-02</encoding-date>
    </encoding>
  </identification>

  <!-- PART LIST -->
  <part-list>
    <score-part id="P1">
      <part-name>Voice</part-name>
    </score-part>
    <score-part id="P2">
      <part-name>Choir (Sustains / Vowel Engine)</part-name>
    </score-part>
    <score-part id="P3">
      <part-name>Violin I</part-name>
    </score-part>
    <score-part id="P4">
      <part-name>Violin II</part-name>
    </score-part>
    <score-part id="P5">
      <part-name>Harp</part-name>
    </score-part>
    <score-part id="P6">
      <part-name>Flamenco Mandolin</part-name>
    </score-part>
    <score-part id="P7">
      <part-name>Trumpet</part-name>
    </score-part>
    <score-part id="P8">
      <part-name>Glockenspiel / Bells</part-name>
    </score-part>
    <score-part id="P9">
      <part-name>Gong / Percussion</part-name>
    </score-part>
  </part-list>

  <!-- GLOBAL METADATA -->
  <!-- Tempo chosen to map 1 beat = 1 second (♩ = 60) so fractional-second rules easier to follow -->
  <!-- The score contains 5 measures (4/4) = 20 beats = 20 seconds (first 20 s as requested) -->

  <!-- PART P1: VOICE (measures 1-5) -->
  <part id="P1">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>        <!-- quarter = 4 divisions -->
        <key>
          <fifths>3</fifths>            <!-- A major (3 sharps) -->
        </key>
        <time>
          <beats>4</beats>
          <beat-type>4</beat-type>
        </time>
        <clef>
          <sign>G</sign>
          <line>2</line>
        </clef>
      </attributes>

      <!-- tempo -->
      <direction placement="above">
        <direction-type>
          <metronome>
            <beat-unit>quarter</beat-unit>
            <per-minute>60</per-minute>
          </metronome>
        </direction-type>
        <sound tempo="60"/>
      </direction>

      <!-- textual performance directions (exact behaviors) -->
      <direction placement="above">
        <direction-type>
          <words>
            <![CDATA[
            PERFORMANCE NOTES (apply exactly):
            - Harp: pulse every 4.3 s for 1.31 s (notated separately in Harp part; also use automation for precise durations).
            - Gong: strike every 9.95 s (one strike falls within measure 3 at approx. beat 1.95).
            - Violins: add one violin voice each second (approx. add in playback); every 2.3–2.4 s all violins drop -23% pitch for 0.7 s then snap back in 0.2 s.
            - Trumpets: add one trumpet every 5 s; each added trumpet tuned 43.11% lower frequency relative to the last violin added (implement via pitch-shift in playback).
            - Choir: hold each repeated vowel for 1 s, each consonant for 1 s (see Choir part).
            ]]>
          </words>
        </direction-type>
      </direction>

      <!-- notated melodic skeleton for singer (one measure of vocal rhythm -- user provided lyrics to align later) -->
      <note>
        <pitch>
          <step>A</step>
          <octave>4</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>Oooh</text>
        </lyric>
      </note>
      <note>
        <pitch>
          <step>G</step>
          <octave>4</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>her</text>
        </lyric>
      </note>
      <note>
        <pitch>
          <step>E</step>
          <octave>4</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>haaair</text>
        </lyric>
      </note>
      <note>
        <rest/>
        <duration>4</duration>
        <type>quarter</type>
      </note>
    </measure>

    <!-- measure 2 -->
    <measure number="2">
      <note>
        <pitch>
          <step>B</step>
          <octave>4</octave>
        </pitch>
        <duration>2</duration>
        <type>half</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>her</text>
        </lyric>
      </note>
      <note>
        <pitch>
          <step>D</step>
          <octave>5</octave>
        </pitch>
        <duration>2</duration>
        <type>half</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>liiips</text>
        </lyric>
      </note>
      <note>
        <pitch>
          <step>C</step>
          <octave>5</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>her</text>
        </lyric>
      </note>
    </measure>

    <!-- measure 3 (gong strike falls here at ~9.95s) -->
    <measure number="3">
      <note>
        <pitch>
          <step>A</step>
          <octave>4</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>smeeels</text>
        </lyric>
      </note>
      <note>
        <pitch>
          <step>G</step>
          <octave>4</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>Her</text>
        </lyric>
      </note>
      <note>
        <rest/>
        <duration>4</duration>
        <type>quarter</type>
      </note>
      <note>
        <rest/>
        <duration>4</duration>
        <type>quarter</type>
      </note>
    </measure>

    <!-- measure 4 -->
    <measure number="4">
      <note>
        <pitch>
          <step>E</step>
          <octave>4</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>A</text>
        </lyric>
      </note>
      <note>
        <pitch>
          <step>F</step>
          <octave>4</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>beell</text>
        </lyric>
      </note>
      <note>
        <pitch>
          <step>E</step>
          <octave>4</octave>
        </pitch>
        <duration>8</duration>
        <type>half</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>for</text>
        </lyric>
      </note>
    </measure>

    <!-- measure 5 (ends the 20-second section) -->
    <measure number="5">
      <note>
        <pitch>
          <step>D</step>
          <octave>4</octave>
        </pitch>
        <duration>8</duration>
        <type>half</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>my</text>
        </lyric>
      </note>
      <note>
        <pitch>
          <step>E</step>
          <octave>4</octave>
        </pitch>
        <duration>8</duration>
        <type>half</type>
        <lyric>
          <syllabic>single</syllabic>
          <text>soouuul</text>
        </lyric>
      </note>
    </measure>

    <!-- final direction: repeat this 3 times; apply +11.232% loudness and harmonic enrichment per repetition -->
    <measure number="6">
      <direction placement="below">
        <direction-type>
          <words>
            <![CDATA[
            REPEAT INSTRUCTION:
            - Repeat measures 1-5 two additional times (3 total plays).
            - Each repetition: overall gain +11.232% relative to previous, and increased harmonic density (add extra violin voices / doubling).
            - After 2 verses (i.e., from verse 3 onward) switch composer-influence cycle as per user blueprint.
            ]]>
          </words>
        </direction-type>
      </direction>
    </measure>
  </part>

  <!-- PART P2: Choir (text engine for vowel/consonant timing) -->
  <part id="P2">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>
        <key>
          <fifths>3</fifths>
        </key>
        <time>
          <beats>4</beats>
          <beat-type>4</beat-type>
        </time>
        <clef>
          <sign>G</sign>
          <line>2</line>
        </clef>
      </attributes>

      <direction placement="above">
        <direction-type>
          <words>
            <![CDATA[
            Choir engine: For every repeated vowel (per the lyric text), sustain that vowel sound for 1.00 s (1 beat at ♩=60).
            For every consonant, produce a 1.00 s voiced consonant articulation.
            For mute consonants/vowels, sing the representative sound as specified by user.
            Implement as sustained syllables in sync with the voice; use a separate sampler patch per vowel for clarity.
            ]]>
          </words>
        </direction-type>
      </direction>

      <!-- notated sustained whole note (placeholder) -->
      <note>
        <pitch>
          <step>A</step>
          <octave>4</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>

    <!-- measure 2-5 copy to preserve note length across the 20s block -->
    <measure number="2">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="3">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="4">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="5">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
  </part>

  <!-- PART P3: Violin I -->
  <part id="P3">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>
        <key>
          <fifths>3</fifths>
        </key>
        <time>
          <beats>4</beats>
          <beat-type>4</beat-type>
        </time>
        <clef>
          <sign>G</sign>
          <line>2</line>
        </clef>
      </attributes>

      <direction placement="above">
        <direction-type>
          <words>
            <![CDATA[
            Violins: start with warm, prominent violin sound (louder than typical). Add one violin voice every 1 second in playback (implement via layered samples / separate tracks).
            Every 2.3–2.4 s, apply a pitch-bend to drop -23% for 0.7 s then snap back in 0.2 s (use pitch automation).
            ]]>
          </words>
        </direction-type>
      </direction>

      <!-- notated sustained line to represent continuous presence -->
      <note>
        <pitch>
          <step>A</step>
          <octave>5</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>

    <!-- measures 2-5 sustain -->
    <measure number="2">
      <note>
        <pitch>
          <step>B</step>
          <octave>5</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="3">
      <note>
        <pitch>
          <step>C</step>
          <octave>6</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="4">
      <note>
        <pitch>
          <step>B</step>
          <octave>5</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="5">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
  </part>

  <!-- PART P4: Violin II (same instructions as Violin I, used for staggered additions) -->
  <part id="P4">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>
        <key>
          <fifths>3</fifths>
        </key>
        <time>
          <beats>4</beats>
          <beat-type>4</beat-type>
        </time>
        <clef>
          <sign>G</sign>
          <line>2</line>
        </clef>
      </attributes>
      <note>
        <pitch>
          <step>F</step>
          <octave>5</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="2">
      <note>
        <pitch>
          <step>G</step>
          <octave>5</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="3">
      <note>
        <pitch>
          <step>A</step>
          <octave>5</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="4">
      <note>
        <pitch>
          <step>B</step>
          <octave>5</octave>
        </pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="5">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
  </part>

  <!-- PART P5: Harp (pulses every 4.3s for 1.31s) -->
  <part id="P5">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>
        <key>
          <fifths>3</fifths>
        </key>
        <time>
          <beats>4</beats>
          <beat-type>4</beat-type>
        </time>
        <clef>
          <sign>G</sign>
          <line>2</line>
        </clef>
      </attributes>

      <direction placement="above">
        <direction-type>
          <words>
            <![CDATA[
            Harp pulses: every 4.3 seconds play a harp arpeggio lasting 1.31 s.
            Notation: approximate pulse on measure positions nearest to 4.3s increments (beat 4.3 ≈ beat 4 + 0.3 of next beat). Use automation/sampler for exact 1.31s durations.
            ]]>
          </words>
        </direction-type>
      </direction>

      <!-- approximate notation: short arpeggio on beat 4 of measure 1 -->
      <note>
        <chord/>
        <pitch><step>A</step><octave>4</octave></pitch>
        <duration>1</duration>
        <type>16th</type>
      </note>
      <note>
        <pitch><step>C</step><octave>5</octave></pitch>
        <duration>1</duration>
        <type>16th</type>
      </note>
      <note>
        <pitch><step>E</step><octave>5</octave></pitch>
        <duration>2</duration>
        <type>eighth</type>
      </note>
      <note>
        <rest/>
        <duration>12</duration>
        <type>quarter</type>
      </note>
    </measure>

    <measure number="2">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
    <measure number="3">
      <note>
        <chord/>
        <pitch><step>B</step><octave>4</octave></pitch>
        <duration>2</duration>
        <type>eighth</type>
      </note>
      <note>
        <pitch><step>D</step><octave>5</octave></pitch>
        <duration>2</duration>
        <type>eighth</type>
      </note>
      <note>
        <rest/>
        <duration>12</duration>
        <type>quarter</type>
      </note>
    </measure>

    <measure number="4">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>

    <measure number="5">
      <note>
        <rest/>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>
  </part>

  <!-- PART P6: Flamenco Mandolin (background rhythmic arpeggio) -->
  <part id="P6">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>
        <key>
          <fifths>3</fifths>
        </key>
        <time>
          <beats>4</beats>
          <beat-type>4</beat-type>
        </time>
        <clef>
          <sign>G</sign>
          <line>2</line>
        </clef>
      </attributes>

      <note>
        <pitch><step>E</step><octave>5</octave></pitch>
        <duration>4</duration>
        <type>quarter</type>
      </note>
      <note>
        <pitch><step>D</step><octave>5</octave></pitch>
        <duration>4</duration>
        <type>quarter</type>
      </note>
      <note>
        <pitch><step>C</step><octave>5</octave></pitch>
        <duration>4</duration>
        <type>quarter</type>
      </note>
      <note>
        <pitch><step>B</step><octave>4</octave></pitch>
        <duration>4</duration>
        <type>quarter</type>
      </note>
    </measure>

    <measure number="2">
      <note><rest/><duration>16</duration><type>whole</type></note>
    </measure>
    <measure number="3">
      <note><rest/><duration>16</duration><type>whole</type></note>
    </measure>
    <measure number="4">
      <note><rest/><duration>16</duration><type>whole</type></note>
    </measure>
    <measure number="5">
      <note><rest/><duration>16</duration><type>whole</type></note>
    </measure>
  </part>

  <!-- PART P7: Trumpet (adds a trumpet every 5 s; pitch relationships indicated in directions) -->
  <part id="P7">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>
        <key><fifths>3</fifths></key>
        <time><beats>4</beats><beat-type>4</beat-type></time>
        <clef><sign>G</sign><line>2</line></clef>
      </attributes>

      <direction placement="above">
        <direction-type>
          <words>
            <![CDATA[
            Trumpets: add one trumpet at approx. 5s, 10s, 15s... Each new trumpet's pitch = 43.11% lower frequency than the previously added violin (implement via pitch-shift).
            Notated here as single sustaining notes to be realized with layered trumpet tracks.
            ]]>
          </words>
        </direction-type>
      </direction>

      <note>
        <pitch><step>C</step><octave>5</octave></pitch>
        <duration>16</duration>
        <type>whole</type>
      </note>
    </measure>

    <measure number="2"><note><rest/><duration>16</duration><type>whole</type></note></measure>
    <measure number="3"><note><rest/><duration>16</duration><type>whole</type></note></measure>
    <measure number="4"><note><rest/><duration>16</duration><type>whole</type></note></measure>
    <measure number="5"><note><rest/><duration>16</duration><type>whole</type></note></measure>
  </part>

  <!-- PART P8: Glockenspiel / Bells -->
  <part id="P8">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>
        <key><fifths>3</fifths></key>
        <time><beats>4</beats><beat-type>4</beat-type></time>
        <clef><sign>G</sign><line>2</line></clef>
      </attributes>

      <direction placement="above">
        <direction-type>
          <words>
            <![CDATA[
            Bells (Glockenspiel): During first 2 verses -> 5 bells continuous (here approximate as regular 8th-note chiming in first 20s).
            Then switch to 4 bells continuous for following two-verse blocks.
            ]]>
          </words>
        </direction-type>
      </direction>

      <!-- simple repeated eighth notes to imply "bells every 2 verses" cycle -->
      <note><pitch><step>G</step><octave>6</octave></pitch><duration>2</duration><type>eighth</type></note>
      <note><pitch><step>E</step><octave>6</octave></pitch><duration>2</duration><type>eighth</type></note>
      <note><pitch><step>D</step><octave>6</octave></pitch><duration>2</duration><type>eighth</type></note>
      <note><pitch><step>B</step><octave>5</octave></pitch><duration>2</duration><type>eighth</type></note>
      <note><pitch><step>G</step><octave>6</octave></pitch><duration>2</duration><type>eighth</type></note>
      <note><rest/><duration>8</duration><type>quarter</type></note>
    </measure>

    <measure number="2"><note><rest/><duration>16</duration><type>whole</type></note></measure>
    <measure number="3"><note><rest/><duration>16</duration><type>whole</type></note></measure>
    <measure number="4"><note><rest/><duration>16</duration><type>whole</type></note></measure>
    <measure number="5"><note><rest/><duration>16</duration><type>whole</type></note></measure>
  </part>

  <!-- PART P9: Gong / Percussion (every 9.95 s -> approx. occurs near measure 3 beat 2) -->
  <part id="P9">
    <measure number="1">
      <attributes>
        <divisions>4</divisions>
        <key><fifths>3</fifths></key>
        <time><beats>4</beats><beat-type>4</beat-type></time>
        <clef><sign>percussion</sign><line>2</line></clef>
      </attributes>

      <direction placement="above">
        <direction-type>
          <words>
            <![CDATA[
            Gong: strike every 9.95 seconds. Expected approx. placement: between measure 2 and 3 (near measure 3 beat 1.95). Match gong level to violin loudness.
            ]]>
          </words>
        </direction-type>
      </direction>

      <!-- placeholder rests; actual strikes to be implemented by sampler at exact times -->
      <note><rest/><duration>16</duration><type>whole</type></note>
    </measure>
    <measure number="2"><note><rest/><duration>16</duration><type>whole</type></note></measure>
    <measure number="3">
      <note>
        <unpitched>
          <display-step>G</display-step>
          <display-octave>3</display-octave>
        </unpitched>
        <duration>1</duration>
        <type>16th</type>
        <notations>
          <tied type="start"/>
        </notations>
      </note>
      <note><rest/><duration>15</duration><type>quarter</type></note>
    </measure>
    <measure number="4"><note><rest/><duration>16</duration><type>whole</type></note></measure>
    <measure number="5"><note><rest/><duration>16</duration><type>whole</type></note></measure>
  </part>

  <!-- final global direction block describing full structure & later composer changes -->
  <part id="P1">
    <measure number="7">
      <direction placement="below">
        <direction-type>
          <words>
            <![CDATA[
            FULL STRUCTURE (user blueprint):
            - Repeat this 20s block to cover the verse text (repeat 3 times with +11.232% loudness each repeat).
            - After first 2 verses, switch influence cycles per user spec in 2-verse blocks:
              Beethoven Violin Concerto (1st mov.), Howard Shore "Destiny Awaits" timbral character, Mendelssohn Violin Concerto (1st mov.), Sibelius Finlandia (first 10s), Tchaikovsky Dance of the Sugar Plum Fairy.
            - After that cycle repeats until end. The entire song repeats 3 times total, and each full song repeat is transposed up by 50% higher key (apply pitch-shift/transposition at render).
            - Cymatic Instagram shapes -> converted into pitch material: use provided sample mapping for each instrument patch in playback engine.
            - Violins: every second another violin is added (use layered tracks) and apply the 2.3–2.4s pitch-drop cycle as automation.
            - Trumpet: add per 5s; each new trumpet tuned 43.11% lower frequency relative to last violin added.
            ]]>
          </words>
        </direction-type>
      </direction>
    </measure>
  </part>

</score-partwise>
