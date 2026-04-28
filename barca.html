<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FC Barcelona Info Design Demo</title>
  <style>
    :root {
      --bg: #07111f;
      --ink: #f6efe5;
      --muted: rgba(246, 239, 229, 0.72);
      --line: rgba(246, 239, 229, 0.14);
      --barca-blue: #004d98;
      --barca-red: #a50044;
      --gold: #f2c14e;
      --panel-shadow: rgba(0, 0, 0, 0.28);
      --barca-stripes: repeating-linear-gradient(
        90deg,
        rgba(165, 0, 68, 0.88) 0 22%,
        rgba(242, 193, 78, 0.82) 22% 23.5%,
        rgba(0, 77, 152, 0.92) 23.5% 45.5%,
        rgba(242, 193, 78, 0.82) 45.5% 47%
      );
      --barca-stripe-size: 420px 100%;
      --page-bg: #0d1725;
      --crest-section-bg: var(--page-bg);
      --deep-section-bg: var(--page-bg);
      --archive-shared-bg: var(--deep-section-bg);
    }

    * {
      box-sizing: border-box;
    }

    html,
    body {
      margin: 0;
      padding: 0;
      background: var(--page-bg);
      color: var(--ink);
      font-family: Georgia, "Times New Roman", serif;
      overflow-x: hidden;
    }

    body::before {
      content: "";
      position: fixed;
      inset: 0;
      pointer-events: none;
      background-image:
        linear-gradient(rgba(255, 255, 255, 0.025) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255, 255, 255, 0.025) 1px, transparent 1px);
      background-size: 36px 36px;
      mask-image: linear-gradient(180deg, rgba(0, 0, 0, 0.45), rgba(0, 0, 0, 0.1));
    }

    .progress {
      position: fixed;
      inset: 0 0 auto 0;
      height: 4px;
      z-index: 50;
      background: rgba(255, 255, 255, 0.08);
    }

    .progress-fill {
      width: 0%;
      height: 100%;
      transform-origin: left center;
      background: linear-gradient(90deg, var(--gold), var(--barca-red), var(--barca-blue));
      box-shadow: 0 0 20px rgba(242, 193, 78, 0.35);
    }

    .hero-shell {
      position: relative;
      height: 210vh;
    }

    .hero-motto {
      position: absolute;
      left: 72%;
      top: 132vh;
      transform: translateX(-50%);
      z-index: 2;
      width: min(38vw, 560px);
      text-align: left;
      pointer-events: none;
      opacity: 0;
      transition: opacity 240ms linear;
    }

    .hero-motto-label {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.74rem;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.72);
      margin-bottom: 1rem;
    }

    .hero-motto-text {
      margin: 0;
      font-family: Georgia, "Times New Roman", serif;
      font-size: clamp(2.2rem, 5vw, 4.8rem);
      line-height: 1;
      letter-spacing: -0.04em;
      color: rgba(246, 239, 229, 0.96);
      text-wrap: balance;
    }

    .hero-motto-rule {
      width: min(180px, 22vw);
      height: 2px;
      margin: 0 0 1.25rem;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.85), transparent);
    }

    .hero-motto-sub {
      margin-top: 1rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.92rem;
      line-height: 1.6;
      color: rgba(246, 239, 229, 0.46);
    }

    .hero {
      height: 100vh;
      padding: 7vw;
      display: flex;
      align-items: center;
      position: sticky;
      top: 0;
      overflow: hidden;
      background: linear-gradient(90deg, var(--barca-red) 0 50%, #213972 50% 100%);
    }

    .hero::before {
      content: "";
      position: absolute;
      inset: 0;
      background:
        linear-gradient(180deg, transparent 0%, transparent 58%, rgba(7, 17, 31, 0.16) 72%, rgba(7, 17, 31, 0.48) 86%, rgba(7, 17, 31, 0.92) 100%),
        linear-gradient(90deg, rgba(0, 0, 0, 0.05), transparent 50%, rgba(0, 0, 0, 0.08)),
        linear-gradient(rgba(255, 255, 255, 0.035) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255, 255, 255, 0.035) 1px, transparent 1px);
      background-size: 100% 100%, auto, 34px 34px, 34px 34px;
      pointer-events: none;
    }

    .hero::after {
      content: "";
      position: absolute;
      top: 50%;
      left: 50%;
      width: min(16vw, 160px);
      aspect-ratio: 1;
      border-radius: 50%;
      transform: translate(-50%, -50%);
      border: 3px solid rgba(242, 193, 78, 0.95);
      box-shadow:
        0 0 0 12px rgba(242, 193, 78, 0.12),
        0 0 46px rgba(0, 0, 0, 0.15);
      pointer-events: none;
    }

    .eyebrow,
    .panel-index,
    .micro-label {
      font-family: Arial, Helvetica, sans-serif;
      letter-spacing: 0.18em;
      text-transform: uppercase;
    }

    .eyebrow {
      color: var(--gold);
      font-size: 0.78rem;
      margin-bottom: 1.25rem;
    }

    h1,
    h2,
    h3 {
      font-family: Didot, "Bodoni 72", "Times New Roman", serif;
      font-weight: 700;
      letter-spacing: -0.04em;
    }

    .stat-value {
      font-family: Arial, Helvetica, sans-serif;
      font-weight: 700;
      letter-spacing: -0.04em;
    }

    .hero h1 {
      margin: 0 0 1rem;
      font-size: clamp(3.2rem, 7vw, 7.2rem);
      line-height: 0.9;
      max-width: 7ch;
    }

    .hero-deck {
      margin: 0 0 1.15rem;
      max-width: 20rem;
      font-size: clamp(1rem, 1.35vw, 1.18rem);
      line-height: 1.5;
      color: rgba(246, 239, 229, 0.9);
      font-family: Arial, Helvetica, sans-serif;
    }

    .hero-copy {
      position: relative;
      z-index: 1;
      max-width: 31rem;
    }

    .hero-crest {
      position: fixed;
      top: 50%;
      left: 75%;
      z-index: 6;
      transform: translate(-50%, -50%);
      width: min(34vw, 430px);
      pointer-events: none;
      will-change: transform, left, top, width;
    }

    .hero-crest.is-locked {
      will-change: auto;
    }

    .crest-mark {
      width: 100%;
      display: block;
      filter: drop-shadow(0 16px 30px rgba(0, 0, 0, 0.22));
    }

    .hero-copy p {
      max-width: 29rem;
      font-size: clamp(0.96rem, 1.1vw, 1rem);
      line-height: 1.7;
      color: var(--muted);
      margin: 0;
    }

    .scroll-hint {
      margin-top: 1.8rem;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.58);
      font-size: 0.92rem;
    }

    .horizontal-section {
      position: relative;
      background: var(--deep-section-bg);
    }

    .sticky-track {
      position: relative;
      overflow: visible;
      background: var(--page-bg);
    }

    .panels {
      display: block;
      width: 100%;
      height: auto;
      position: relative;
      z-index: 1;
    }

    .panel {
      width: 100%;
      min-height: 100vh;
      padding: 5.6vw;
      display: grid;
      grid-template-columns: 1.05fr 0.95fr;
      gap: 3vw;
      align-items: center;
      position: relative;
      overflow: hidden;
    }

    .panel-main,
    .panel-side {
      position: relative;
      z-index: 1;
    }

    .panel::before {
      content: "";
      position: absolute;
      inset: 0;
      background:
        radial-gradient(circle at 20% 20%, rgba(242, 193, 78, 0.12), transparent 24%),
        linear-gradient(135deg, rgba(255, 255, 255, 0.04), transparent 50%);
      pointer-events: none;
    }

    .panel:nth-child(1) {
      background: var(--deep-section-bg);
    }

    .panel:nth-child(1)::before {
      background: none;
    }

    .panel:nth-child(1) .panel-main {
      max-width: 42rem;
      padding: 1.6rem 1.75rem 1.7rem 0;
    }

    .panel:nth-child(1) .lede,
    .panel:nth-child(1) .detail {
      max-width: 31rem;
    }

    .panel:nth-child(1) .panel-side {
      gap: 1.2rem;
    }

    .colors-opening {
      min-height: 100vh;
      padding: 0;
      display: block;
      background: var(--deep-section-bg);
      overflow: hidden;
      isolation: isolate;
    }

    .colors-opening::before {
      background: none;
    }

    .colors-opening-shell {
      position: relative;
      min-height: 100vh;
      padding: 2.8rem 4.5vw 2.5rem;
      overflow: hidden;
      background: transparent;
    }

    .colors-opening-shell::before {
      display: none;
    }

    .colors-opening-shell::after {
      display: none;
    }

    .colors-signature,
    .colors-copy,
    .colors-palette,
    .colors-boundary-indicator {
      position: relative;
      z-index: 3;
    }

    .colors-signature {
      width: min(92%, 760px);
      margin-top: 0.2rem;
      margin-left: 2vw;
    }

    .colors-copy {
      width: min(38vw, 34rem);
      margin-top: 8vh;
      margin-left: 2vw;
    }

    .colors-copy h2 {
      margin: 0;
      font-family: Didot, "Bodoni 72", "Times New Roman", serif;
      font-size: clamp(4.2rem, 9vw, 8.2rem);
      line-height: 0.88;
      letter-spacing: -0.08em;
      color: rgba(248, 241, 232, 0.98);
      text-shadow: 0 24px 54px rgba(0, 0, 0, 0.28);
      text-wrap: balance;
    }

    .colors-copy-kicker {
      margin-top: 1.8rem;
      display: flex;
      align-items: center;
      gap: 1rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.9rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.92);
    }

    .colors-copy-kicker-line {
      width: 56px;
      height: 1px;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.92), rgba(242, 193, 78, 0.12));
    }

    .colors-copy-lede,
    .colors-copy-detail {
      max-width: 26rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: clamp(0.98rem, 1.15vw, 1.08rem);
      line-height: 1.64;
      color: rgba(246, 239, 229, 0.84);
    }

    .colors-copy-lede {
      margin: 1.55rem 0 0.7rem;
    }

    .colors-copy-detail {
      margin: 0;
      color: rgba(246, 239, 229, 0.56);
    }

    .colors-energy,
    .colors-collision-cloud,
    .colors-collision-turbulence,
    .colors-collision-shimmer,
    .colors-stripes {
      display: none;
    }

    .colors-boundary-indicator {
      display: none;
    }

    .colors-palette {
      position: absolute;
      right: 4.6vw;
      top: 16vh;
      width: min(35vw, 620px);
      display: grid;
      gap: 1rem;
      z-index: 4;
    }

    .palette-node {
      width: 100%;
      border: 1px solid rgba(242, 193, 78, 0.24);
      border-radius: 28px;
      background:
        linear-gradient(180deg, rgba(13, 23, 37, 0.92), rgba(8, 16, 31, 0.96)),
        rgba(13, 23, 37, 0.9);
      padding: 0;
      display: grid;
      grid-template-columns: 116px 1fr 62px;
      align-items: stretch;
      overflow: hidden;
      color: inherit;
      cursor: pointer;
      text-align: left;
      min-height: 5.5rem;
      box-shadow: 0 18px 42px rgba(0, 0, 0, 0.14);
      backdrop-filter: blur(14px);
      transition: transform 220ms ease, border-color 220ms ease, box-shadow 220ms ease, grid-template-columns 240ms ease, min-height 240ms ease, background 220ms ease;
    }

    .palette-node:hover,
    .palette-node:focus-visible {
      transform: translateY(-2px);
      border-color: rgba(242, 193, 78, 0.46);
      box-shadow: 0 22px 48px rgba(0, 0, 0, 0.18);
      outline: none;
    }

    .palette-node.is-expanded {
      grid-template-columns: 152px 1fr 68px;
      min-height: 8rem;
      background:
        linear-gradient(180deg, rgba(15, 26, 41, 0.96), rgba(8, 17, 32, 0.98)),
        rgba(13, 23, 37, 0.94);
    }

    .palette-node-swatch {
      position: relative;
      min-height: 5.5rem;
      overflow: hidden;
      background-color: rgba(255, 255, 255, 0.05);
    }

    .palette-node-swatch::before,
    .palette-node-swatch::after {
      content: "";
      position: absolute;
      inset: 0;
    }

    .palette-node-swatch.is-red::before {
      background:
        radial-gradient(circle at 34% 46%, rgba(255, 87, 155, 0.34), transparent 0 5.6rem),
        linear-gradient(135deg, rgba(93, 0, 33, 0.76), rgba(165, 0, 68, 0.96));
    }

    .palette-node-swatch.is-red::after {
      background:
        linear-gradient(132deg, transparent 0 42%, rgba(255, 132, 184, 0.16) 42% 46%, transparent 46% 100%),
        repeating-radial-gradient(circle at 58% 42%, rgba(255, 191, 215, 0.1) 0 1.5px, transparent 1.5px 10px);
      opacity: 0.85;
    }

    .palette-node-swatch.is-blue::before {
      background:
        radial-gradient(circle at 34% 48%, rgba(102, 181, 255, 0.3), transparent 0 5.5rem),
        linear-gradient(135deg, rgba(0, 29, 76, 0.82), rgba(0, 77, 152, 0.98));
    }

    .palette-node-swatch.is-blue::after {
      background:
        linear-gradient(228deg, transparent 0 44%, rgba(140, 199, 255, 0.14) 44% 48%, transparent 48% 100%),
        repeating-radial-gradient(circle at 52% 40%, rgba(196, 230, 255, 0.1) 0 1.5px, transparent 1.5px 10px);
      opacity: 0.82;
    }

    .palette-node-swatch.is-gold::before {
      background:
        radial-gradient(circle at 34% 48%, rgba(255, 241, 195, 0.28), transparent 0 5rem),
        linear-gradient(135deg, rgba(126, 88, 0, 0.82), rgba(242, 193, 78, 0.98));
    }

    .palette-node-swatch.is-gold::after {
      background:
        linear-gradient(130deg, transparent 0 42%, rgba(255, 249, 220, 0.2) 42% 46%, transparent 46% 100%),
        repeating-radial-gradient(circle at 54% 40%, rgba(255, 245, 209, 0.1) 0 1.5px, transparent 1.5px 10px);
      opacity: 0.82;
    }

    .palette-node-copy {
      padding: 0.95rem 1.35rem 0.95rem 1.1rem;
      display: grid;
      align-content: center;
      gap: 0.35rem;
    }

    .palette-node-role,
    .palette-node-meta {
      font-family: Arial, Helvetica, sans-serif;
      letter-spacing: 0.18em;
      text-transform: uppercase;
    }

    .palette-node-role {
      font-size: 0.74rem;
      color: rgba(242, 193, 78, 0.68);
    }

    .palette-node-name {
      font-family: Didot, "Bodoni 72", "Times New Roman", serif;
      font-size: clamp(1.5rem, 2vw, 2.2rem);
      line-height: 1;
      color: rgba(248, 241, 232, 0.98);
    }

    .palette-node-note {
      max-height: 0;
      opacity: 0;
      overflow: hidden;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.92rem;
      line-height: 1.5;
      color: rgba(246, 239, 229, 0.68);
      transition: max-height 240ms ease, opacity 220ms ease, margin-top 220ms ease;
    }

    .palette-node-meta {
      max-height: 0;
      opacity: 0;
      overflow: hidden;
      font-size: 0.72rem;
      color: rgba(242, 193, 78, 0.52);
      transition: max-height 240ms ease, opacity 220ms ease, margin-top 220ms ease;
    }

    .palette-node.is-expanded .palette-node-note {
      max-height: 5rem;
      opacity: 1;
      margin-top: 0.35rem;
    }

    .palette-node.is-expanded .palette-node-meta {
      max-height: 1.2rem;
      opacity: 1;
      margin-top: 0.2rem;
    }

    .palette-node-toggle {
      position: relative;
      align-self: center;
      justify-self: center;
      width: 42px;
      height: 42px;
      border-radius: 50%;
      border: 1px solid rgba(242, 193, 78, 0.55);
    }

    .palette-node-toggle::before,
    .palette-node-toggle::after {
      content: "";
      position: absolute;
      left: 50%;
      top: 50%;
      background: rgba(242, 193, 78, 0.92);
      transform: translate(-50%, -50%);
      transition: transform 200ms ease, opacity 200ms ease;
    }

    .palette-node-toggle::before {
      width: 14px;
      height: 1.5px;
    }

    .palette-node-toggle::after {
      width: 1.5px;
      height: 14px;
    }

    .palette-node.is-expanded .palette-node-toggle::after {
      opacity: 0;
      transform: translate(-50%, -50%) scaleY(0.2);
    }


    .panel:nth-child(2) {
      background: var(--deep-section-bg);
    }

    #crestPanel {
      min-height: 100vh;
      display: block;
      margin-top: -22vh;
      padding-top: calc(4.5vw + 22vh);
      padding-bottom: 7vw;
      background: var(--archive-shared-bg);
      overflow: visible;
    }

    #crestPanel::before {
      display: none;
    }

    .crest-archive-panel {
      min-height: 100vh;
    }

    .crest-archive-layout {
      display: grid;
      grid-template-columns: 1fr;
      grid-template-rows: minmax(0, 1fr) auto;
      gap: 0;
      align-items: stretch;
      min-height: 100%;
      justify-items: center;
    }

    .crest-timeline-column {
      width: 100%;
      min-height: 18rem;
      align-self: end;
      position: relative;
      min-width: 0;
    }

    .crest-preview-column {
      width: 100%;
      min-width: 0;
      position: relative;
      display: grid;
      justify-items: start;
      align-items: start;
      min-height: calc(100vh - 19rem);
    }

    .crest-preview-sticky {
      position: sticky;
      top: 5vh;
      width: min(100%, 44rem);
      z-index: 6;
      display: grid;
      justify-items: start;
      justify-content: start;
      text-align: left;
      gap: 0.35rem;
      padding-top: 0.25rem;
      opacity: var(--crest-enter-progress);
      transform: translateY(calc((1 - var(--crest-enter-progress)) * 18px));
    }

    .crest-preview-sticky.is-floating {
      position: fixed;
      top: 5vh;
      left: var(--crest-preview-left, 0px);
      width: min(var(--crest-preview-width, 704px), 44rem);
      z-index: 8;
      transform: translateY(calc((1 - var(--crest-enter-progress)) * 18px));
    }

    .crest-preview-sticky.is-bottom {
      position: absolute;
      left: 0;
      bottom: 23rem;
      top: auto;
      width: min(100%, 44rem);
      z-index: 6;
      transform: translateY(calc((1 - var(--crest-enter-progress)) * 18px));
    }

    .crest-preview-sticky .headline-rule {
      display: block;
      width: min(36vw, 320px);
      margin-bottom: 0.8rem;
    }

    .crest-preview-sticky .panel-index {
      margin-bottom: 0.2rem;
    }

    .crest-preview-sticky > h2 {
      margin: 0;
      font-size: clamp(2.4rem, 5vw, 4.9rem);
      line-height: 0.92;
      letter-spacing: -0.05em;
      max-width: none;
      white-space: nowrap;
    }

    .crest-preview-header {
      display: none;
      align-items: center;
      justify-content: center;
      gap: 0.7rem;
      flex-wrap: wrap;
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      position: relative;
      z-index: 9;
    }

    .crest-preview-era {
      font-size: clamp(0.92rem, 1.2vw, 1rem);
      font-weight: 700;
      letter-spacing: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(255, 249, 238, 0.96);
    }

    .crest-preview-tag {
      font-size: 0.56rem;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.72);
      font-family: Arial, Helvetica, sans-serif;
    }

    .crest-preview-note,
    .crest-preview-meta {
      display: none;
    }

    .crest-stage {
      position: relative;
      min-height: 0;
      margin-bottom: 1rem;
      padding: 0;
      width: min(100%, 16rem);
      min-height: 0;
      display: grid;
      place-items: center;
      border-radius: 0;
      border: 0;
      background: transparent;
      box-shadow: none;
    }

    .crest-photo {
      display: block;
      width: min(24vw, 250px);
      max-height: 220px;
      object-fit: contain;
      filter:
        drop-shadow(1px 0 0 rgba(255, 255, 255, 0.96))
        drop-shadow(-1px 0 0 rgba(255, 255, 255, 0.96))
        drop-shadow(0 1px 0 rgba(255, 255, 255, 0.96))
        drop-shadow(0 -1px 0 rgba(255, 255, 255, 0.96))
        drop-shadow(1px 1px 0 rgba(255, 255, 255, 0.92))
        drop-shadow(-1px 1px 0 rgba(255, 255, 255, 0.92))
        drop-shadow(1px -1px 0 rgba(255, 255, 255, 0.92))
        drop-shadow(-1px -1px 0 rgba(255, 255, 255, 0.92))
        drop-shadow(0 14px 22px rgba(0, 0, 0, 0.16));
    }

    #crestPanel {
      --crest-fade-progress: 0;
      --crest-enter-progress: 0;
    }

    #crestPanel .crest-preview-sticky,
    #crestPanel .crest-preview-floating,
    #crestPanel .crest-era-list,
    #crestPanel .crest-timeline-rail {
      transition: opacity 220ms ease;
    }

    #crestPanel.is-handing-off .crest-preview-sticky,
    #crestPanel.is-handing-off .crest-preview-floating,
    #crestPanel.is-handing-off .crest-era-list,
    #crestPanel.is-handing-off .crest-timeline-rail {
      opacity: calc(1 - var(--crest-fade-progress));
    }

    .crest-timeline-rail {
      position: sticky;
      top: calc(50vh + 13.5rem);
      transform: translateY(calc(-50% + ((1 - var(--crest-enter-progress)) * 14px)));
      width: 100%;
      height: 14rem;
      overflow: visible;
      z-index: 2;
      border: 0;
      border-radius: 0;
      background: transparent;
      box-shadow: none;
      opacity: var(--crest-enter-progress);
    }

    .crest-active-guide {
      position: absolute;
      left: 0;
      right: 0;
      top: 1.5rem;
      height: 0;
      pointer-events: none;
      z-index: 6;
    }

    .crest-active-guide-triangle {
      position: absolute;
      left: var(--crest-guide-x, 50%);
      top: -1px;
      width: 0;
      height: 0;
      border-left: 7px solid transparent;
      border-right: 7px solid transparent;
      border-top: 10px solid rgba(242, 193, 78, 0.92);
      transform: translateX(-50%);
      filter: drop-shadow(0 1px 4px rgba(0, 0, 0, 0.18));
      transition: left 240ms ease;
    }

    .crest-timeline-rail::after {
      display: none;
    }

    .crest-timeline-rail.is-floating {
      position: fixed;
      top: calc(50vh + 13.5rem);
      left: var(--crest-timeline-left, 0px);
      width: var(--crest-timeline-width, 100%);
      height: 14rem;
      overflow: visible;
      z-index: 7;
      transform: translateY(calc(-50% + ((1 - var(--crest-enter-progress)) * 14px)));
    }

    .crest-timeline-rail.is-bottom {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 7vw;
      top: auto;
      width: 100%;
      height: 14rem;
      overflow: visible;
      z-index: 2;
      transform: translateY(calc((1 - var(--crest-enter-progress)) * 14px));
    }

    .crest-era-list {
      position: relative;
      display: flex;
      align-items: flex-start;
      gap: clamp(2.4rem, 3vw, 3.2rem);
      min-width: max-content;
      padding: 3rem 0 2.1rem;
      transition: transform 240ms ease;
      will-change: transform;
    }

    .crest-era-list::before {
      content: "";
      position: absolute;
      left: 0;
      right: 0;
      top: 2.2rem;
      height: 2px;
      border-radius: 999px;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.2), rgba(242, 193, 78, 0.58));
      box-shadow: none;
      transform-origin: left center;
    }

    .crest-era-step {
      flex: 0 0 clamp(170px, 13vw, 190px);
      display: grid;
      grid-template-rows: auto auto 1fr;
      justify-items: center;
      text-align: center;
      position: relative;
      isolation: isolate;
      min-height: 150px;
      padding: 0 0.5rem 0;
      border-radius: 0;
      background: transparent;
      border: 0;
      backdrop-filter: none;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.52);
      transition: color 180ms ease, transform 220ms ease, opacity 220ms ease;
    }

    .crest-era-step::before {
      content: "";
      position: absolute;
      top: 2.2rem;
      left: calc(50% + 2.2rem);
      width: calc(100% + clamp(2.4rem, 3vw, 3.2rem) - 4.4rem);
      height: 2px;
      border-radius: 999px;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.34), rgba(242, 193, 78, 0.14));
      z-index: 0;
    }

    .crest-era-step:last-child::before {
      display: none;
    }

    .crest-era-dot {
      position: relative;
      width: clamp(44px, 4.2vw, 52px);
      aspect-ratio: 1;
      margin-top: 0.15rem;
      border-radius: 50%;
      border: 1px solid rgba(242, 193, 78, 0.52);
      background: rgba(8, 18, 38, 0.5);
      display: grid;
      place-items: center;
      color: rgba(242, 193, 78, 0.86);
      font-size: clamp(0.94rem, 1.1vw, 1.08rem);
      font-weight: 700;
      line-height: 1;
      letter-spacing: -0.03em;
      z-index: 1;
      transition: transform 180ms ease, border-color 180ms ease, color 180ms ease, background 180ms ease;
    }

    .crest-preview-floating {
      position: absolute;
      left: 50%;
      top: 7.1rem;
      width: min(22vw, 240px);
      display: grid;
      justify-items: center;
      gap: 0;
      z-index: 4;
      pointer-events: none;
      opacity: var(--crest-enter-progress);
      transform: translateX(-50%) translateY(calc((1 - var(--crest-enter-progress)) * 12px));
    }

    .crest-timeline-rail.is-floating .crest-preview-floating {
      position: fixed;
      left: 50%;
      top: calc(50% - 16rem);
      z-index: 9;
      transform: translate(-50%, calc(-50% + ((1 - var(--crest-enter-progress)) * 12px)));
    }

    .crest-timeline-rail.is-bottom .crest-preview-floating {
      position: absolute;
      left: 50%;
      top: -10rem;
      transform: translateX(-50%) translateY(calc((1 - var(--crest-enter-progress)) * 12px));
    }

    .crest-preview-floating::before {
      display: none;
    }

    .crest-stage {
      width: min(100%, 230px);
      min-height: 0;
      padding: 0;
      border-radius: 0;
      border: 0;
      background: transparent;
      box-shadow: none;
      overflow: visible;
    }

    .crest-stage::after {
      display: none;
    }

    .crest-preview-floating .crest-photo {
      width: min(100%, 250px);
      max-height: 230px;
      filter:
        drop-shadow(1px 0 0 rgba(255, 255, 255, 0.96))
        drop-shadow(-1px 0 0 rgba(255, 255, 255, 0.96))
        drop-shadow(0 1px 0 rgba(255, 255, 255, 0.96))
        drop-shadow(0 -1px 0 rgba(255, 255, 255, 0.96))
        drop-shadow(1px 1px 0 rgba(255, 255, 255, 0.92))
        drop-shadow(-1px 1px 0 rgba(255, 255, 255, 0.92))
        drop-shadow(1px -1px 0 rgba(255, 255, 255, 0.92))
        drop-shadow(-1px -1px 0 rgba(255, 255, 255, 0.92))
        drop-shadow(0 18px 26px rgba(0, 0, 0, 0.22));
    }

    .crest-preview-copy {
      width: min(320px, 100%);
      display: grid;
      gap: 0.5rem;
      justify-items: center;
      text-align: center;
      opacity: 0.92;
    }

    .crest-preview-copy .crest-preview-note {
      margin-bottom: 0;
      max-width: 24rem;
      font-size: 0.92rem;
      line-height: 1.65;
      color: rgba(246, 239, 229, 0.72);
    }

    .crest-era-dot::before {
      display: none;
    }

    .crest-era-drop {
      width: 1px;
      height: 22px;
      margin-top: 0.55rem;
      border-radius: 999px;
      background: linear-gradient(180deg, rgba(242, 193, 78, 0.54), rgba(242, 193, 78, 0.1));
      opacity: 1;
    }

    .crest-era-copy {
      display: grid;
      justify-items: center;
      gap: 0.42rem;
      width: 100%;
      margin-top: 0.48rem;
      padding: 0;
      border-top: 0;
    }

    .crest-era-kicker {
      font-size: 0.55rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.48);
      padding-left: 0.18em;
    }

    .crest-era-label {
      display: grid;
      gap: 0.34rem;
      justify-items: center;
      width: min(100%, 16ch);
    }

    .crest-era-rule {
      width: min(100%, 116px);
      height: 4px;
    }

    .crest-era-rule::before {
      top: 3px;
      background: rgba(242, 193, 78, 0.18);
    }

    .crest-era-rule::after {
      left: calc(50% - 3px);
      top: 0;
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: rgba(242, 193, 78, 0.68);
      box-shadow: none;
    }

    .crest-era-year {
      font-size: clamp(1rem, 1.2vw, 1.15rem);
      font-weight: 700;
      letter-spacing: -0.03em;
      color: rgba(246, 239, 229, 0.94);
      white-space: nowrap;
    }

    .crest-era-style {
      font-size: 0.58rem;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.36);
    }

    .crest-era-step.is-active {
      color: rgba(246, 239, 229, 0.92);
      transform: translateY(-1px);
    }

    .crest-era-step.is-active .crest-era-dot {
      color: rgba(255, 238, 201, 0.96);
      border-color: rgba(242, 193, 78, 0.88);
      background: rgba(8, 18, 38, 0.72);
      transform: scale(1.02);
    }

    .crest-era-step.is-active .crest-era-year {
      color: rgba(255, 255, 255, 0.98);
    }

    .crest-era-step.is-active .crest-era-style {
      color: rgba(242, 193, 78, 0.76);
    }

    .crest-era-step.is-active .crest-era-kicker {
      color: rgba(255, 223, 151, 0.92);
    }

    .crest-era-step.is-active .crest-era-drop {
      opacity: 1;
    }

    .panel.legacy-ten-panel {
      --legacy-exit-progress: 0;
      position: relative;
      background: var(--deep-section-bg);
      margin-top: -1px;
      padding-top: calc(5.6vw + 1px);
      grid-template-columns: minmax(0, 0.9fr) minmax(320px, 0.88fr);
      align-content: center;
    }

    .panel.legacy-ten-panel::before {
      background: none;
    }

    .legacy-ten-panel .panel-main {
      position: relative;
      grid-column: 2;
      padding-top: clamp(8rem, 14vh, 11rem);
      max-width: 30rem;
      z-index: 2;
      opacity: calc(1 - var(--legacy-exit-progress));
      transform: translateY(calc(var(--legacy-exit-progress) * -36px));
      transition: opacity 180ms ease, transform 180ms ease;
    }

    .legacy-ten-panel .panel-side {
      grid-column: 2;
      align-self: stretch;
      align-content: center;
      opacity: calc(1 - var(--legacy-exit-progress));
      transform: translateY(calc(var(--legacy-exit-progress) * -28px));
      transition: opacity 180ms ease, transform 180ms ease;
    }

    .legacy-ten-stage {
      min-height: 0;
      display: grid;
      align-content: center;
      justify-items: start;
      padding-left: 0;
      max-width: 20rem;
    }

    .legacy-ten-kicker {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.8rem;
      letter-spacing: 0.26em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.78);
      margin-bottom: 1rem;
    }

    .legacy-ten-caption {
      max-width: 18rem;
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.7;
      color: rgba(246, 239, 229, 0.62);
    }

    .legacy-ten-orb {
      position: fixed;
      left: 0;
      top: 0;
      color: rgba(247, 232, 194, 0.98);
      font-family: Arial, Helvetica, sans-serif;
      font-size: clamp(5.8rem, 8vw, 7.6rem);
      font-weight: 800;
      letter-spacing: -0.12em;
      line-height: 0.88;
      text-shadow:
        0 18px 48px rgba(0, 0, 0, 0.34),
        0 0 36px rgba(242, 193, 78, 0.12);
      text-rendering: geometricPrecision;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      backface-visibility: hidden;
      transform-style: preserve-3d;
      filter: drop-shadow(0 24px 54px rgba(0, 0, 0, 0.3));
      opacity: 0;
      pointer-events: none;
      z-index: 45;
      transform: translate(-50%, -50%) scale(1);
      transform-origin: center center;
      will-change: transform, opacity, left, top;
    }

    .legacy-ten-orb.is-visible {
      opacity: 1;
    }

    .player-spotlight-panel {
      --player-enter-progress: 1;
      min-height: 112vh;
      grid-template-columns: minmax(320px, 0.9fr) minmax(360px, 1.1fr);
      gap: 4vw;
      align-items: center;
      background: var(--crest-section-bg);
      overflow: visible;
    }

    #maradonaPanel {
      --player-enter-progress: 0;
      --player-side-progress: 1;
      --maradona-side-entry-progress: 0;
      background: var(--deep-section-bg);
      grid-template-columns: minmax(320px, 0.9fr) minmax(360px, 1.1fr);
      gap: 4vw;
      align-items: center;
      position: relative;
    }

    #maradonaPanel::after,
    #romarioPanel::after,
    #rivaldoPanel::after,
    #ronaldinhoPanel::after,
    #messiPanel::after,
    #yamalPanel::after {
      content: "";
      position: absolute;
      top: 2rem;
      bottom: 2rem;
      left: 44.8%;
      width: 1px;
      background: rgba(255, 255, 255, 0.12);
      pointer-events: none;
      transform: translateX(-0.5px);
      opacity: calc(var(--player-enter-progress) * 0.8);
    }

    #maradonaPanel .panel-main {
      align-self: start;
      max-width: none;
      padding: 2.4rem 2.8rem 3rem 1.8rem;
      opacity: 1;
      transform: none;
    }

    #maradonaPanel .panel-side {
      align-self: start;
      justify-items: end;
      background: none;
      opacity: var(--player-side-progress);
      pointer-events: none;
      transform:
        translateX(calc((1 - var(--maradona-side-entry-progress)) * 180px))
        translateY(calc((1 - var(--maradona-side-entry-progress)) * 12px));
    }

    #maradonaPanel .panel-side.is-fixed,
    #maradonaPanel .panel-side.is-bottom,
    #maradonaPanel .panel-side.is-fade-fixed {
      background: none;
    }

    #maradonaPanel .panel-index {
      position: relative;
      display: flex;
      align-items: center;
      gap: 1.75rem;
      margin-bottom: 0.7rem;
      color: rgba(242, 193, 78, 0.88);
    }

    #maradonaPanel .panel-index::before {
      content: "";
      width: 42px;
      height: 52px;
      flex: 0 0 auto;
      background: center / contain no-repeat url("/Users/eddy/Desktop/Barca 10/Barca Gold.png");
      filter: none;
      opacity: 1;
    }

    #maradonaPanel .panel-index::after {
      content: "";
      position: absolute;
      left: calc(42px + 0.9rem);
      top: 50%;
      width: 1px;
      height: 3.2rem;
      background: rgba(242, 193, 78, 0.62);
      transform: translateY(-50%);
    }

    #maradonaPanel .headline-rule {
      width: min(92%, 760px);
      height: 1px;
      margin-bottom: 1.6rem;
      border-radius: 0;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.72), rgba(242, 193, 78, 0.18));
    }

    #maradonaPanel .player-kicker {
      display: none;
    }

    #maradonaPanel h2 {
      max-width: 9ch;
      margin: 0;
      font-size: clamp(4.1rem, 6.2vw, 6.5rem);
      line-height: 0.88;
      letter-spacing: -0.08em;
      text-wrap: balance;
    }

    .maradona-accent-bar {
      display: flex;
      gap: 0;
      margin: 1.55rem 0 1.35rem;
      width: fit-content;
    }

    .maradona-accent-bar span {
      display: block;
      height: 4px;
      border-radius: 999px;
    }

    .maradona-accent-bar span:first-child {
      width: 4rem;
      background: var(--barca-red);
    }

    .maradona-accent-bar span:last-child {
      width: 4.7rem;
      background: var(--barca-blue);
    }

    #maradonaPanel .lede,
    #maradonaPanel .detail {
      max-width: 44rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.95rem;
      line-height: 1.55;
      color: rgba(246, 239, 229, 0.84);
    }

    #maradonaPanel .detail {
      margin-top: 1.45rem;
      padding-top: 1rem;
      border-top: 0;
      color: rgba(246, 239, 229, 0.76);
    }

    #maradonaPanel .detail::before {
      content: "";
      display: block;
      width: 2rem;
      height: 1px;
      margin-bottom: 1.2rem;
      background: rgba(242, 193, 78, 0.72);
    }

    #maradonaPanel .player-stats-board {
      margin-top: 1.9rem;
      padding: 1.25rem 1.35rem 1.4rem;
      border-radius: 0;
      border: 1px solid rgba(242, 193, 78, 0.34);
      background: rgba(5, 11, 22, 0.44);
      box-shadow: none;
      backdrop-filter: none;
    }

    #maradonaPanel .player-group-title {
      color: rgba(242, 193, 78, 0.82);
      letter-spacing: 0.24em;
      margin-bottom: 1rem;
    }

    #maradonaPanel .season-card + .season-card {
      margin-top: 0.95rem;
      padding-top: 0.95rem;
    }

    #maradonaPanel .season-header {
      margin-bottom: 0.78rem;
    }

    #maradonaPanel .season-year {
      font-family: "DIN Condensed", "Arial Narrow", Arial, sans-serif;
      font-size: 0.98rem;
      font-weight: 700;
      letter-spacing: 0.14em;
    }

    #maradonaPanel .season-summary {
      color: rgba(242, 193, 78, 0.78);
    }

    #maradonaPanel .season-stat-row {
      padding: 0.7rem 0;
      border-top: 1px solid rgba(255, 255, 255, 0.08);
    }

    #maradonaPanel .player-stat-value {
      font-family: "DIN Condensed", "Arial Narrow", Arial, sans-serif;
      font-weight: 700;
      letter-spacing: 0;
    }

    #maradonaPanel .season-stat-row:first-of-type {
      border-top: 1px solid rgba(255, 255, 255, 0.08);
    }

    #maradonaPanel .player-portrait-wrap {
      width: min(46vw, 680px);
      height: 100vh;
      align-self: end;
      transform: none;
      overflow: visible;
    }

    #maradonaPanel .player-flag-layer {
      position: absolute;
      top: 5%;
      right: calc(-1 * var(--player-side-right, 5.6vw) + 0.2vw);
      bottom: 9%;
      left: -5.2vw;
      border-radius: 0;
      overflow: hidden;
      clip-path: inset(0);
      -webkit-mask-image:
        linear-gradient(to right, transparent 0%, rgba(0, 0, 0, 0.08) 6%, rgba(0, 0, 0, 0.42) 14%, rgba(0, 0, 0, 0.76) 22%, #000 31%, #000 69%, rgba(0, 0, 0, 0.76) 78%, rgba(0, 0, 0, 0.42) 86%, rgba(0, 0, 0, 0.08) 94%, transparent 100%),
        linear-gradient(to bottom, transparent 0%, rgba(0, 0, 0, 0.08) 7%, rgba(0, 0, 0, 0.4) 16%, rgba(0, 0, 0, 0.74) 24%, #000 34%, #000 66%, rgba(0, 0, 0, 0.74) 76%, rgba(0, 0, 0, 0.4) 84%, rgba(0, 0, 0, 0.08) 93%, transparent 100%);
      -webkit-mask-composite: source-in;
      mask-image:
        linear-gradient(to right, transparent 0%, rgba(0, 0, 0, 0.08) 6%, rgba(0, 0, 0, 0.42) 14%, rgba(0, 0, 0, 0.76) 22%, #000 31%, #000 69%, rgba(0, 0, 0, 0.76) 78%, rgba(0, 0, 0, 0.42) 86%, rgba(0, 0, 0, 0.08) 94%, transparent 100%),
        linear-gradient(to bottom, transparent 0%, rgba(0, 0, 0, 0.08) 7%, rgba(0, 0, 0, 0.4) 16%, rgba(0, 0, 0, 0.74) 24%, #000 34%, #000 66%, rgba(0, 0, 0, 0.74) 76%, rgba(0, 0, 0, 0.4) 84%, rgba(0, 0, 0, 0.08) 93%, transparent 100%);
      mask-composite: intersect;
      opacity: 0.76;
      filter: saturate(1.06) brightness(1.2) contrast(1.04);
      display: flex;
      align-items: center;
      justify-content: flex-end;
    }

    #maradonaPanel .player-flag-layer::before,
    #maradonaPanel .player-flag-layer::after {
      content: "";
      position: absolute;
      inset: 0;
      pointer-events: none;
      z-index: 1;
    }

    #maradonaPanel .player-flag-layer::before {
      background:
        radial-gradient(circle at 52% 44%, rgba(255, 255, 255, 0.05), transparent 36%),
        radial-gradient(circle at 18% 46%, rgba(255, 255, 255, 0.06), transparent 32%),
        linear-gradient(90deg, rgba(8, 17, 31, 0.2) 0%, rgba(8, 17, 31, 0.08) 18%, rgba(8, 17, 31, 0.03) 40%, rgba(8, 17, 31, 0.08) 68%, rgba(8, 17, 31, 0.18) 100%),
        linear-gradient(180deg, rgba(8, 17, 31, 0.22) 0%, rgba(8, 17, 31, 0.06) 24%, rgba(8, 17, 31, 0.03) 58%, rgba(8, 17, 31, 0.16) 100%);
      mix-blend-mode: multiply;
      opacity: 0.72;
    }

    #maradonaPanel .player-flag-layer::after {
      inset: -6%;
      background:
        radial-gradient(circle at 50% 52%, rgba(11, 21, 37, 0) 36%, rgba(11, 21, 37, 0.08) 58%, rgba(11, 21, 37, 0.18) 76%, rgba(11, 21, 37, 0.3) 100%);
      filter: blur(36px);
      opacity: 0.42;
    }

    #maradonaPanel .player-flag-layer img {
      position: relative;
      z-index: 0;
      width: 108%;
      height: 108%;
      min-width: 0;
      max-width: none;
      object-fit: cover;
      object-position: 58% center;
      clip-path: inset(0);
      filter: blur(0.8px) saturate(0.82) brightness(0.76) contrast(0.96);
    }

    #maradonaPanel .player-name-overlay {
      top: 44%;
      left: -1.6vw;
      z-index: 3;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      width: max-content;
      font-family: Didot, "Bodoni 72", "Times New Roman", serif;
      line-height: 0.88;
      letter-spacing: 0;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.9);
      text-shadow: 0 10px 24px rgba(0, 0, 0, 0.18);
      mix-blend-mode: screen;
    }

    #maradonaPanel .player-name-overlay .outline {
      position: relative;
      display: inline-block;
      margin-left: 0.15rem;
      margin-bottom: 0.55rem;
      padding-bottom: 0;
      color: rgba(242, 193, 78, 0.88);
      -webkit-text-stroke: 0;
      text-stroke: 0;
      opacity: 0.92;
      font-size: clamp(1.8rem, 2.2vw, 2.35rem);
      letter-spacing: 0.42em;
      line-height: 1;
    }

    #maradonaPanel .player-name-overlay .outline::after {
      display: none;
    }

    #maradonaPanel .player-name-overlay .display-name {
      position: relative;
      display: block;
      margin-left: -0.05rem;
      margin-bottom: 0.72rem;
      padding-bottom: 0.58rem;
      font-size: clamp(5.9rem, 6.7vw, 7rem);
      letter-spacing: -0.045em;
      line-height: 0.9;
      color: rgba(245, 213, 148, 0.96);
    }

    #maradonaPanel .player-name-overlay .display-name::after {
      content: "";
      position: absolute;
      left: 0;
      bottom: 0;
      width: min(16vw, 330px);
      height: 1px;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.86), rgba(242, 193, 78, 0.14));
    }

    #maradonaPanel .player-name-caption {
      margin-top: 0;
      margin-left: 0.18rem;
      display: flex;
      flex-direction: column;
      gap: 0.22rem;
      font-family: Didot, "Bodoni 72", "Times New Roman", serif;
      color: rgba(242, 193, 78, 0.88);
      line-height: 1;
    }

    #maradonaPanel .player-name-caption span {
      display: block;
      font-size: clamp(0.76rem, 0.95vw, 0.98rem);
      letter-spacing: 0.3em;
    }

    #maradonaPanel .player-portrait-wrap::before {
      content: "";
      display: block;
      position: absolute;
      left: 2%;
      right: -4%;
      bottom: -6%;
      height: 42%;
      background:
        radial-gradient(ellipse at 26% 92%, rgba(0, 77, 152, 0.82) 0%, rgba(0, 77, 152, 0.44) 18%, rgba(0, 77, 152, 0.16) 34%, rgba(0, 77, 152, 0) 58%),
        radial-gradient(ellipse at 80% 96%, rgba(165, 0, 68, 0.86) 0%, rgba(165, 0, 68, 0.46) 20%, rgba(165, 0, 68, 0.16) 36%, rgba(165, 0, 68, 0) 62%),
        radial-gradient(ellipse at 54% 100%, rgba(242, 193, 78, 0.14) 0%, rgba(242, 193, 78, 0.06) 16%, rgba(242, 193, 78, 0) 40%);
      filter: blur(42px);
      opacity: 1;
      mix-blend-mode: screen;
      pointer-events: none;
      z-index: 1;
    }

    #maradonaPanel .player-portrait {
      position: relative;
      z-index: 2;
      height: 100vh;
      object-position: 70% bottom;
      transform: translateX(6%) translateY(0) scale(1.14);
      transform-origin: center bottom;
    }

    #romarioPanel,
    #rivaldoPanel,
    #ronaldinhoPanel,
    #messiPanel,
    #yamalPanel {
      --player-enter-progress: 0;
      --player-side-progress: 0;
      --player-side-entry-progress: 0;
      --player-name-top: 43%;
      --player-name-left: -1.8vw;
      --player-outline-size: clamp(1.8rem, 2.2vw, 2.35rem);
      --player-display-size: clamp(5.8rem, 6.5vw, 6.8rem);
      --player-display-line-width: min(16vw, 330px);
      --player-caption-size: clamp(0.76rem, 0.95vw, 0.98rem);
      --player-portrait-object-position: 70% bottom;
      --player-portrait-transform: translateX(6%) translateY(0) scale(1.08);
      --player-flag-image-position: 58% center;
    }

    #romarioPanel .panel-main,
    #rivaldoPanel .panel-main,
    #ronaldinhoPanel .panel-main,
    #messiPanel .panel-main,
    #yamalPanel .panel-main {
      align-self: start;
      max-width: none;
      padding: 2.4rem 2.8rem 3rem 1.8rem;
      opacity: 1;
      transform: none;
    }

    #romarioPanel .panel-side,
    #rivaldoPanel .panel-side,
    #ronaldinhoPanel .panel-side,
    #messiPanel .panel-side,
    #yamalPanel .panel-side {
      align-self: start;
      justify-items: end;
      background: none;
      opacity: var(--player-side-progress);
      pointer-events: none;
      transform:
        translateX(calc((1 - var(--player-side-entry-progress, var(--player-enter-progress))) * 180px))
        translateY(calc((1 - var(--player-side-entry-progress, var(--player-enter-progress))) * 12px));
    }

    #romarioPanel .panel-index,
    #rivaldoPanel .panel-index,
    #ronaldinhoPanel .panel-index,
    #messiPanel .panel-index,
    #yamalPanel .panel-index {
      position: relative;
      display: flex;
      align-items: center;
      gap: 1.75rem;
      margin-bottom: 0.7rem;
      color: rgba(242, 193, 78, 0.88);
    }

    #romarioPanel .panel-index::before,
    #rivaldoPanel .panel-index::before,
    #ronaldinhoPanel .panel-index::before,
    #messiPanel .panel-index::before,
    #yamalPanel .panel-index::before {
      content: "";
      width: 42px;
      height: 52px;
      flex: 0 0 auto;
      background: center / contain no-repeat url("/Users/eddy/Desktop/Barca 10/Barca Gold.png");
      filter: none;
      opacity: 1;
    }

    #romarioPanel .panel-index::after,
    #rivaldoPanel .panel-index::after,
    #ronaldinhoPanel .panel-index::after,
    #messiPanel .panel-index::after,
    #yamalPanel .panel-index::after {
      content: "";
      position: absolute;
      left: calc(42px + 0.9rem);
      top: 50%;
      width: 1px;
      height: 3.2rem;
      background: rgba(242, 193, 78, 0.62);
      transform: translateY(-50%);
    }

    #romarioPanel .headline-rule,
    #rivaldoPanel .headline-rule,
    #ronaldinhoPanel .headline-rule,
    #messiPanel .headline-rule,
    #yamalPanel .headline-rule {
      width: min(92%, 760px);
      height: 1px;
      margin-bottom: 1.6rem;
      border-radius: 0;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.72), rgba(242, 193, 78, 0.18));
    }

    #romarioPanel .player-kicker,
    #rivaldoPanel .player-kicker,
    #ronaldinhoPanel .player-kicker,
    #messiPanel .player-kicker,
    #yamalPanel .player-kicker {
      display: none;
    }

    #romarioPanel h2,
    #rivaldoPanel h2,
    #ronaldinhoPanel h2,
    #messiPanel h2,
    #yamalPanel h2 {
      max-width: 9ch;
      margin: 0;
      font-size: clamp(4.1rem, 6.2vw, 6.5rem);
      line-height: 0.88;
      letter-spacing: -0.08em;
      text-wrap: balance;
    }

    #romarioPanel .maradona-accent-bar,
    #rivaldoPanel .maradona-accent-bar,
    #ronaldinhoPanel .maradona-accent-bar,
    #messiPanel .maradona-accent-bar,
    #yamalPanel .maradona-accent-bar {
      display: flex;
      gap: 0;
      margin: 1.55rem 0 1.35rem;
      width: fit-content;
    }

    #romarioPanel .maradona-accent-bar span,
    #rivaldoPanel .maradona-accent-bar span,
    #ronaldinhoPanel .maradona-accent-bar span,
    #messiPanel .maradona-accent-bar span,
    #yamalPanel .maradona-accent-bar span {
      display: block;
      height: 4px;
      border-radius: 999px;
    }

    #romarioPanel .maradona-accent-bar span:first-child,
    #rivaldoPanel .maradona-accent-bar span:first-child,
    #ronaldinhoPanel .maradona-accent-bar span:first-child,
    #messiPanel .maradona-accent-bar span:first-child,
    #yamalPanel .maradona-accent-bar span:first-child {
      width: 4rem;
      background: var(--barca-red);
    }

    #romarioPanel .maradona-accent-bar span:last-child,
    #rivaldoPanel .maradona-accent-bar span:last-child,
    #ronaldinhoPanel .maradona-accent-bar span:last-child,
    #messiPanel .maradona-accent-bar span:last-child,
    #yamalPanel .maradona-accent-bar span:last-child {
      width: 4.7rem;
      background: var(--barca-blue);
    }

    #romarioPanel .lede,
    #romarioPanel .detail,
    #rivaldoPanel .lede,
    #rivaldoPanel .detail,
    #ronaldinhoPanel .lede,
    #ronaldinhoPanel .detail,
    #messiPanel .lede,
    #messiPanel .detail,
    #yamalPanel .lede,
    #yamalPanel .detail {
      max-width: 44rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.95rem;
      line-height: 1.55;
      color: rgba(246, 239, 229, 0.84);
    }

    #romarioPanel .detail,
    #rivaldoPanel .detail,
    #ronaldinhoPanel .detail,
    #messiPanel .detail,
    #yamalPanel .detail {
      margin-top: 1.45rem;
      padding-top: 1rem;
      border-top: 0;
      color: rgba(246, 239, 229, 0.76);
    }

    #romarioPanel .detail::before,
    #rivaldoPanel .detail::before,
    #ronaldinhoPanel .detail::before,
    #messiPanel .detail::before,
    #yamalPanel .detail::before {
      content: "";
      display: block;
      width: 2rem;
      height: 1px;
      margin-bottom: 1.2rem;
      background: rgba(242, 193, 78, 0.72);
    }

    #romarioPanel .player-stats-board,
    #rivaldoPanel .player-stats-board,
    #ronaldinhoPanel .player-stats-board,
    #messiPanel .player-stats-board,
    #yamalPanel .player-stats-board {
      margin-top: 1.9rem;
      padding: 1.25rem 1.35rem 1.4rem;
      border-radius: 0;
      border: 1px solid rgba(242, 193, 78, 0.34);
      background: rgba(5, 11, 22, 0.44);
      box-shadow: none;
      backdrop-filter: none;
    }

    #romarioPanel .player-group-title,
    #rivaldoPanel .player-group-title,
    #ronaldinhoPanel .player-group-title,
    #messiPanel .player-group-title,
    #yamalPanel .player-group-title {
      color: rgba(242, 193, 78, 0.82);
      letter-spacing: 0.24em;
      margin-bottom: 1rem;
    }

    #romarioPanel .season-card + .season-card,
    #rivaldoPanel .season-card + .season-card,
    #ronaldinhoPanel .season-card + .season-card,
    #messiPanel .season-card + .season-card,
    #yamalPanel .season-card + .season-card {
      margin-top: 0.95rem;
      padding-top: 0.95rem;
    }

    #romarioPanel .season-header,
    #rivaldoPanel .season-header,
    #ronaldinhoPanel .season-header,
    #messiPanel .season-header,
    #yamalPanel .season-header {
      margin-bottom: 0.78rem;
    }

    #romarioPanel .season-year,
    #rivaldoPanel .season-year,
    #ronaldinhoPanel .season-year,
    #messiPanel .season-year,
    #yamalPanel .season-year {
      font-family: "DIN Condensed", "Arial Narrow", Arial, sans-serif;
      font-size: 0.98rem;
      font-weight: 700;
      letter-spacing: 0.14em;
    }

    #romarioPanel .season-summary,
    #rivaldoPanel .season-summary,
    #ronaldinhoPanel .season-summary,
    #messiPanel .season-summary,
    #yamalPanel .season-summary {
      color: rgba(242, 193, 78, 0.78);
    }

    #romarioPanel .season-stat-row,
    #rivaldoPanel .season-stat-row,
    #ronaldinhoPanel .season-stat-row,
    #messiPanel .season-stat-row,
    #yamalPanel .season-stat-row {
      padding: 0.7rem 0;
      border-top: 1px solid rgba(255, 255, 255, 0.08);
    }

    #romarioPanel .player-stat-value,
    #rivaldoPanel .player-stat-value,
    #ronaldinhoPanel .player-stat-value,
    #messiPanel .player-stat-value,
    #yamalPanel .player-stat-value {
      font-family: "DIN Condensed", "Arial Narrow", Arial, sans-serif;
      font-weight: 700;
      letter-spacing: 0;
    }

    #romarioPanel .player-portrait-wrap,
    #rivaldoPanel .player-portrait-wrap,
    #ronaldinhoPanel .player-portrait-wrap,
    #messiPanel .player-portrait-wrap,
    #yamalPanel .player-portrait-wrap {
      width: min(46vw, 680px);
      height: 100vh;
      align-self: end;
      transform: none;
      overflow: visible;
    }

    #romarioPanel .player-flag-layer,
    #rivaldoPanel .player-flag-layer,
    #ronaldinhoPanel .player-flag-layer,
    #messiPanel .player-flag-layer,
    #yamalPanel .player-flag-layer {
      position: absolute;
      top: 5%;
      right: calc(-1 * var(--player-side-right, 5.6vw) + 0.2vw);
      bottom: 9%;
      left: -5.2vw;
      border-radius: 0;
      overflow: hidden;
      clip-path: inset(0);
      -webkit-mask-image:
        linear-gradient(to right, transparent 0%, rgba(0, 0, 0, 0.08) 6%, rgba(0, 0, 0, 0.42) 14%, rgba(0, 0, 0, 0.76) 22%, #000 31%, #000 69%, rgba(0, 0, 0, 0.76) 78%, rgba(0, 0, 0, 0.42) 86%, rgba(0, 0, 0, 0.08) 94%, transparent 100%),
        linear-gradient(to bottom, transparent 0%, rgba(0, 0, 0, 0.08) 7%, rgba(0, 0, 0, 0.4) 16%, rgba(0, 0, 0, 0.74) 24%, #000 34%, #000 66%, rgba(0, 0, 0, 0.74) 76%, rgba(0, 0, 0, 0.4) 84%, rgba(0, 0, 0, 0.08) 93%, transparent 100%);
      -webkit-mask-composite: source-in;
      mask-image:
        linear-gradient(to right, transparent 0%, rgba(0, 0, 0, 0.08) 6%, rgba(0, 0, 0, 0.42) 14%, rgba(0, 0, 0, 0.76) 22%, #000 31%, #000 69%, rgba(0, 0, 0, 0.76) 78%, rgba(0, 0, 0, 0.42) 86%, rgba(0, 0, 0, 0.08) 94%, transparent 100%),
        linear-gradient(to bottom, transparent 0%, rgba(0, 0, 0, 0.08) 7%, rgba(0, 0, 0, 0.4) 16%, rgba(0, 0, 0, 0.74) 24%, #000 34%, #000 66%, rgba(0, 0, 0, 0.74) 76%, rgba(0, 0, 0, 0.4) 84%, rgba(0, 0, 0, 0.08) 93%, transparent 100%);
      mask-composite: intersect;
      opacity: 0.76;
      filter: saturate(1.06) brightness(1.2) contrast(1.04);
      display: flex;
      align-items: center;
      justify-content: flex-end;
    }

    #romarioPanel .player-flag-layer,
    #rivaldoPanel .player-flag-layer,
    #ronaldinhoPanel .player-flag-layer {
      -webkit-mask-image:
        radial-gradient(circle at 50% 50%, #000 0%, #000 48%, rgba(0, 0, 0, 0.92) 60%, rgba(0, 0, 0, 0.72) 70%, rgba(0, 0, 0, 0.36) 82%, rgba(0, 0, 0, 0.08) 92%, transparent 100%),
        linear-gradient(to right, transparent 0%, rgba(0, 0, 0, 0.1) 7%, rgba(0, 0, 0, 0.46) 15%, rgba(0, 0, 0, 0.8) 24%, #000 33%, #000 67%, rgba(0, 0, 0, 0.8) 76%, rgba(0, 0, 0, 0.46) 85%, rgba(0, 0, 0, 0.1) 93%, transparent 100%),
        linear-gradient(to bottom, transparent 0%, rgba(0, 0, 0, 0.1) 8%, rgba(0, 0, 0, 0.44) 17%, rgba(0, 0, 0, 0.78) 26%, #000 35%, #000 65%, rgba(0, 0, 0, 0.78) 74%, rgba(0, 0, 0, 0.44) 83%, rgba(0, 0, 0, 0.1) 92%, transparent 100%);
      mask-image:
        radial-gradient(circle at 50% 50%, #000 0%, #000 48%, rgba(0, 0, 0, 0.92) 60%, rgba(0, 0, 0, 0.72) 70%, rgba(0, 0, 0, 0.36) 82%, rgba(0, 0, 0, 0.08) 92%, transparent 100%),
        linear-gradient(to right, transparent 0%, rgba(0, 0, 0, 0.1) 7%, rgba(0, 0, 0, 0.46) 15%, rgba(0, 0, 0, 0.8) 24%, #000 33%, #000 67%, rgba(0, 0, 0, 0.8) 76%, rgba(0, 0, 0, 0.46) 85%, rgba(0, 0, 0, 0.1) 93%, transparent 100%),
        linear-gradient(to bottom, transparent 0%, rgba(0, 0, 0, 0.1) 8%, rgba(0, 0, 0, 0.44) 17%, rgba(0, 0, 0, 0.78) 26%, #000 35%, #000 65%, rgba(0, 0, 0, 0.78) 74%, rgba(0, 0, 0, 0.44) 83%, rgba(0, 0, 0, 0.1) 92%, transparent 100%);
      opacity: 0.66;
    }

    #romarioPanel .player-flag-layer::before,
    #romarioPanel .player-flag-layer::after,
    #rivaldoPanel .player-flag-layer::before,
    #rivaldoPanel .player-flag-layer::after,
    #ronaldinhoPanel .player-flag-layer::before,
    #ronaldinhoPanel .player-flag-layer::after,
    #messiPanel .player-flag-layer::before,
    #messiPanel .player-flag-layer::after,
    #yamalPanel .player-flag-layer::before,
    #yamalPanel .player-flag-layer::after {
      content: "";
      position: absolute;
      inset: 0;
      pointer-events: none;
      z-index: 1;
    }

    #romarioPanel .player-flag-layer::before,
    #rivaldoPanel .player-flag-layer::before,
    #ronaldinhoPanel .player-flag-layer::before,
    #messiPanel .player-flag-layer::before,
    #yamalPanel .player-flag-layer::before {
      background:
        radial-gradient(circle at 52% 44%, rgba(255, 255, 255, 0.05), transparent 36%),
        radial-gradient(circle at 18% 46%, rgba(255, 255, 255, 0.06), transparent 32%),
        linear-gradient(90deg, rgba(8, 17, 31, 0.2) 0%, rgba(8, 17, 31, 0.08) 18%, rgba(8, 17, 31, 0.03) 40%, rgba(8, 17, 31, 0.08) 68%, rgba(8, 17, 31, 0.18) 100%),
        linear-gradient(180deg, rgba(8, 17, 31, 0.22) 0%, rgba(8, 17, 31, 0.06) 24%, rgba(8, 17, 31, 0.03) 58%, rgba(8, 17, 31, 0.16) 100%);
      mix-blend-mode: multiply;
      opacity: 0.72;
    }

    #romarioPanel .player-flag-layer::after,
    #rivaldoPanel .player-flag-layer::after,
    #ronaldinhoPanel .player-flag-layer::after,
    #messiPanel .player-flag-layer::after,
    #yamalPanel .player-flag-layer::after {
      inset: -6%;
      background:
        radial-gradient(circle at 50% 52%, rgba(11, 21, 37, 0) 36%, rgba(11, 21, 37, 0.08) 58%, rgba(11, 21, 37, 0.18) 76%, rgba(11, 21, 37, 0.3) 100%);
      filter: blur(36px);
      opacity: 0.42;
    }

    #romarioPanel .player-flag-layer::before,
    #rivaldoPanel .player-flag-layer::before,
    #ronaldinhoPanel .player-flag-layer::before {
      background:
        radial-gradient(circle at 50% 50%, rgba(255, 255, 255, 0.04), transparent 34%),
        radial-gradient(circle at 18% 26%, rgba(255, 255, 255, 0.04), transparent 24%),
        radial-gradient(circle at 84% 74%, rgba(8, 17, 31, 0.22), transparent 22%),
        linear-gradient(90deg, rgba(8, 17, 31, 0.34) 0%, rgba(8, 17, 31, 0.12) 18%, rgba(8, 17, 31, 0.05) 40%, rgba(8, 17, 31, 0.12) 68%, rgba(8, 17, 31, 0.3) 100%),
        linear-gradient(180deg, rgba(8, 17, 31, 0.34) 0%, rgba(8, 17, 31, 0.12) 22%, rgba(8, 17, 31, 0.05) 56%, rgba(8, 17, 31, 0.28) 100%);
      opacity: 0.68;
    }

    #romarioPanel .player-flag-layer::after,
    #rivaldoPanel .player-flag-layer::after,
    #ronaldinhoPanel .player-flag-layer::after {
      inset: -8%;
      background:
        radial-gradient(circle at 50% 50%, rgba(11, 21, 37, 0) 38%, rgba(11, 21, 37, 0.06) 58%, rgba(11, 21, 37, 0.14) 76%, rgba(11, 21, 37, 0.24) 100%);
      filter: blur(44px);
      opacity: 0.34;
    }

    #romarioPanel .player-flag-layer img,
    #rivaldoPanel .player-flag-layer img,
    #ronaldinhoPanel .player-flag-layer img,
    #messiPanel .player-flag-layer img,
    #yamalPanel .player-flag-layer img {
      position: relative;
      z-index: 0;
      width: 108%;
      height: 108%;
      min-width: 0;
      max-width: none;
      object-fit: cover;
      object-position: var(--player-flag-image-position);
      clip-path: inset(0);
      filter: blur(0.8px) saturate(0.82) brightness(0.76) contrast(0.96);
    }

    #romarioPanel .player-name-overlay,
    #rivaldoPanel .player-name-overlay,
    #ronaldinhoPanel .player-name-overlay,
    #messiPanel .player-name-overlay,
    #yamalPanel .player-name-overlay {
      top: var(--player-name-top);
      left: var(--player-name-left);
      z-index: 3;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      width: max-content;
      font-family: Didot, "Bodoni 72", "Times New Roman", serif;
      line-height: 0.88;
      letter-spacing: 0;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.9);
      text-shadow: 0 10px 24px rgba(0, 0, 0, 0.18);
      mix-blend-mode: screen;
    }

    #romarioPanel .player-name-overlay .outline,
    #rivaldoPanel .player-name-overlay .outline,
    #ronaldinhoPanel .player-name-overlay .outline,
    #messiPanel .player-name-overlay .outline,
    #yamalPanel .player-name-overlay .outline {
      position: relative;
      display: var(--player-outline-display, inline-block);
      margin-left: 0.15rem;
      margin-bottom: 0.55rem;
      color: rgba(242, 193, 78, 0.88);
      -webkit-text-stroke: 0;
      text-stroke: 0;
      opacity: 0.92;
      font-size: var(--player-outline-size);
      letter-spacing: 0.42em;
      line-height: 1;
    }

    #romarioPanel .player-name-overlay .display-name,
    #rivaldoPanel .player-name-overlay .display-name,
    #ronaldinhoPanel .player-name-overlay .display-name,
    #messiPanel .player-name-overlay .display-name,
    #yamalPanel .player-name-overlay .display-name {
      position: relative;
      display: block;
      margin-left: -0.05rem;
      margin-bottom: 0.72rem;
      padding-bottom: 0.58rem;
      font-size: var(--player-display-size);
      letter-spacing: -0.045em;
      line-height: 0.9;
      color: rgba(245, 213, 148, 0.96);
    }

    #romarioPanel .player-name-overlay .display-name::after,
    #rivaldoPanel .player-name-overlay .display-name::after,
    #ronaldinhoPanel .player-name-overlay .display-name::after,
    #messiPanel .player-name-overlay .display-name::after,
    #yamalPanel .player-name-overlay .display-name::after {
      content: "";
      position: absolute;
      left: 0;
      bottom: 0;
      width: var(--player-display-line-width);
      height: 1px;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.86), rgba(242, 193, 78, 0.14));
    }

    #romarioPanel .player-name-caption,
    #rivaldoPanel .player-name-caption,
    #ronaldinhoPanel .player-name-caption,
    #messiPanel .player-name-caption,
    #yamalPanel .player-name-caption {
      margin-top: 0;
      margin-left: 0.18rem;
      display: flex;
      flex-direction: column;
      gap: 0.22rem;
      font-family: Didot, "Bodoni 72", "Times New Roman", serif;
      color: rgba(242, 193, 78, 0.88);
      line-height: 1;
    }

    #romarioPanel .player-name-caption span,
    #rivaldoPanel .player-name-caption span,
    #ronaldinhoPanel .player-name-caption span,
    #messiPanel .player-name-caption span,
    #yamalPanel .player-name-caption span {
      display: block;
      font-size: var(--player-caption-size);
      letter-spacing: 0.3em;
    }

    #romarioPanel .player-portrait-wrap::before,
    #rivaldoPanel .player-portrait-wrap::before,
    #ronaldinhoPanel .player-portrait-wrap::before,
    #messiPanel .player-portrait-wrap::before,
    #yamalPanel .player-portrait-wrap::before {
      content: "";
      display: block;
      position: absolute;
      left: 2%;
      right: -4%;
      bottom: -6%;
      height: 42%;
      background:
        radial-gradient(ellipse at 26% 92%, rgba(0, 77, 152, 0.82) 0%, rgba(0, 77, 152, 0.44) 18%, rgba(0, 77, 152, 0.16) 34%, rgba(0, 77, 152, 0) 58%),
        radial-gradient(ellipse at 80% 96%, rgba(165, 0, 68, 0.86) 0%, rgba(165, 0, 68, 0.46) 20%, rgba(165, 0, 68, 0.16) 36%, rgba(165, 0, 68, 0) 62%),
        radial-gradient(ellipse at 54% 100%, rgba(242, 193, 78, 0.14) 0%, rgba(242, 193, 78, 0.06) 16%, rgba(242, 193, 78, 0) 40%);
      filter: blur(42px);
      opacity: 1;
      mix-blend-mode: screen;
      pointer-events: none;
      z-index: 1;
    }

    #romarioPanel .player-portrait,
    #rivaldoPanel .player-portrait,
    #ronaldinhoPanel .player-portrait,
    #messiPanel .player-portrait,
    #yamalPanel .player-portrait {
      position: relative;
      z-index: 2;
      height: 100vh;
      object-position: var(--player-portrait-object-position);
      transform: var(--player-portrait-transform);
      transform-origin: center bottom;
    }

    #romarioPanel {
      --player-portrait-object-position: 82% bottom;
      --player-portrait-transform: translateX(16%) translateY(36%) scale(1.5);
      --player-flag-image-position: 54% center;
      --player-name-top: 21%;
      --player-outline-display: none;
    }

    #rivaldoPanel {
      --player-portrait-object-position: 72% bottom;
      --player-portrait-transform: translateX(3%) translateY(0) scale(0.95);
      --player-flag-image-position: 54% center;
      --player-name-top: 70%;
      --player-outline-display: none;
    }

    #ronaldinhoPanel {
      --player-portrait-object-position: 76% bottom;
      --player-portrait-transform: translateX(9%) translateY(0) scale(0.98);
      --player-flag-image-position: 52% center;
      --player-name-top: 23%;
      --player-display-size: clamp(5.3rem, 6.1vw, 6.2rem);
      --player-outline-display: none;
    }

    #messiPanel {
      --player-portrait-object-position: 76% bottom;
      --player-portrait-transform: translateX(8%) translateY(0) scale(0.94);
      --player-flag-image-position: 60% center;
      --player-name-top: 23.5%;
      --player-name-left: -1.2vw;
      --player-display-size: clamp(6rem, 6.7vw, 7rem);
    }

    #yamalPanel {
      --player-portrait-object-position: 82% bottom;
      --player-portrait-transform: translateX(14%) translateY(20%) scale(1.08);
      --player-flag-image-position: 55% center;
      --player-name-top: 52%;
      --player-name-left: -1vw;
    }

    .player-spotlight-panel::before {
      content: "";
      position: absolute;
      inset: 0;
      background: none;
      opacity: calc(var(--player-enter-progress) * 0.85);
      pointer-events: none;
    }

    .player-spotlight-panel .panel-main,
    .player-spotlight-panel .panel-side {
      opacity: var(--player-enter-progress);
    }

    .player-spotlight-panel .panel-main {
      transform: translateY(calc((1 - var(--player-enter-progress)) * 38px));
    }

    .player-spotlight-panel .panel-main {
      max-width: 42rem;
    }

    .player-kicker {
      font-size: 0.82rem;
      letter-spacing: 0.28em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.82);
      margin-bottom: 1rem;
      padding-left: 0.28em;
      font-family: Arial, Helvetica, sans-serif;
    }

    .player-stats-board {
      margin-top: 1.8rem;
      padding: 1.4rem 1.45rem 1.55rem;
      border-radius: 28px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      background: rgba(9, 16, 29, 0.7);
      box-shadow: 0 24px 70px rgba(0, 0, 0, 0.22);
      backdrop-filter: blur(12px);
    }

    .player-group-title {
      font-size: 0.76rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.54);
      margin-bottom: 0.9rem;
      font-family: Arial, Helvetica, sans-serif;
    }

    .career-total-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.85rem;
      margin-bottom: 1.1rem;
    }

    .career-total-card {
      padding: 1rem 1.05rem;
      border-radius: 20px;
      border: 1px solid rgba(255, 255, 255, 0.08);
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.06), rgba(255, 255, 255, 0.02)),
        rgba(7, 17, 31, 0.58);
    }

    .career-total-label,
    .career-ledger-label,
    .career-era-year {
      font-family: Arial, Helvetica, sans-serif;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.5);
      font-size: 0.68rem;
    }

    .career-total-value {
      margin-top: 0.42rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: clamp(1.8rem, 2.7vw, 2.6rem);
      font-weight: 700;
      letter-spacing: -0.06em;
      color: rgba(246, 239, 229, 0.98);
      line-height: 0.92;
    }

    .career-total-sub {
      margin-top: 0.38rem;
      font-size: 0.85rem;
      line-height: 1.45;
      color: rgba(246, 239, 229, 0.62);
      font-family: Arial, Helvetica, sans-serif;
    }

    .career-ledger {
      display: grid;
      gap: 0.78rem;
      margin-top: 0.2rem;
    }

    .career-ledger-row {
      display: grid;
      grid-template-columns: minmax(120px, 0.8fr) minmax(0, 1.3fr) auto;
      gap: 0.9rem;
      align-items: center;
      padding: 0.85rem 0;
      border-top: 1px solid rgba(255, 255, 255, 0.08);
    }

    .career-ledger-row:first-of-type {
      border-top: none;
      padding-top: 0.15rem;
    }

    .career-ledger-note,
    .career-era-copy p {
      margin: 0;
      font-size: 0.92rem;
      line-height: 1.55;
      color: rgba(246, 239, 229, 0.7);
      font-family: Arial, Helvetica, sans-serif;
    }

    .career-ledger-value {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 1rem;
      font-weight: 700;
      color: rgba(242, 193, 78, 0.92);
      text-align: right;
      white-space: nowrap;
    }

    .career-honours {
      display: flex;
      flex-wrap: wrap;
      gap: 0.7rem;
      margin-top: 0.45rem;
    }

    .career-honour-chip {
      min-width: 8.5rem;
      padding: 0.72rem 0.86rem 0.78rem;
      border-radius: 18px;
      border: 1px solid rgba(255, 255, 255, 0.08);
      background: rgba(255, 255, 255, 0.04);
    }

    .career-honour-count {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 1.45rem;
      font-weight: 700;
      letter-spacing: -0.06em;
      color: rgba(242, 193, 78, 0.96);
      line-height: 1;
    }

    .career-honour-name {
      margin-top: 0.28rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.8rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.62);
    }

    .career-era-list {
      display: grid;
      gap: 0.82rem;
      margin-top: 0.4rem;
    }

    .career-era-item {
      display: grid;
      grid-template-columns: 108px minmax(0, 1fr);
      gap: 1rem;
      align-items: start;
      padding-top: 0.82rem;
      border-top: 1px solid rgba(255, 255, 255, 0.08);
    }

    .career-era-item:first-child {
      border-top: none;
      padding-top: 0;
    }

    .career-era-title {
      margin: 0 0 0.3rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 1rem;
      font-weight: 700;
      letter-spacing: -0.03em;
      color: rgba(246, 239, 229, 0.95);
    }


    .season-card + .season-card {
      margin-top: 1.1rem;
      padding-top: 1.1rem;
      border-top: 1px solid rgba(255, 255, 255, 0.08);
    }

    .season-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 1rem;
      margin-bottom: 0.95rem;
      font-family: Arial, Helvetica, sans-serif;
    }

    .season-year {
      font-size: 1.05rem;
      font-weight: 700;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: rgba(255, 248, 228, 0.96);
    }

    .season-summary {
      font-size: 0.78rem;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.44);
    }

    .season-stat-row + .season-stat-row {
      margin-top: 0.85rem;
    }

    .player-stat-meta {
      display: flex;
      align-items: baseline;
      justify-content: space-between;
      gap: 1rem;
      margin-bottom: 0.42rem;
      font-family: Arial, Helvetica, sans-serif;
    }

    .player-stat-label {
      font-size: 0.92rem;
      color: rgba(246, 239, 229, 0.74);
      letter-spacing: 0.04em;
      text-transform: uppercase;
    }

    .player-stat-value {
      font-size: 1.25rem;
      font-weight: 700;
      color: rgba(255, 248, 228, 0.98);
      letter-spacing: -0.04em;
    }

    .player-stat-bar {
      position: relative;
      height: 12px;
      border-radius: 999px;
      overflow: hidden;
      background: rgba(255, 255, 255, 0.08);
    }

    .player-stat-bar span {
      position: absolute;
      inset: 0 auto 0 0;
      width: var(--fill, 0%);
      border-radius: inherit;
      background:
        linear-gradient(90deg, rgba(242, 193, 78, 1), rgba(242, 193, 78, 0.42));
      box-shadow: 0 0 18px rgba(242, 193, 78, 0.22);
    }

    .player-stat-bar.is-assist span {
      background:
        linear-gradient(90deg, rgba(0, 77, 152, 0.96), rgba(111, 166, 234, 0.58));
      box-shadow: 0 0 18px rgba(0, 77, 152, 0.22);
    }

    .player-stat-bar.is-trophy span {
      background:
        linear-gradient(90deg, rgba(165, 0, 68, 0.92), rgba(242, 193, 78, 0.88));
      box-shadow: 0 0 18px rgba(165, 0, 68, 0.22);
    }

    .player-stat-bar.is-apps {
      height: 14px;
      background: rgba(255, 255, 255, 0.06);
    }

    .player-stat-bar.is-apps span {
      background:
        linear-gradient(90deg, rgba(246, 239, 229, 0.96), rgba(242, 193, 78, 0.7));
      box-shadow: 0 0 18px rgba(246, 239, 229, 0.12);
    }

    .player-stat-icons {
      display: flex;
      flex-wrap: wrap;
      gap: 0.34rem;
      padding-top: 0.08rem;
    }

    .stat-icon {
      display: block;
      width: 16px;
      height: 16px;
      flex: 0 0 auto;
      object-fit: contain;
      object-position: center;
      filter: drop-shadow(0 0 8px rgba(255, 248, 228, 0.08));
    }

    .stat-icon.is-assist {
      width: 18px;
      height: 18px;
    }

    .season-trophies {
      display: flex;
      flex-wrap: wrap;
      gap: 0.55rem;
      margin-top: 1rem;
    }

    .trophy-badge {
      display: inline-flex;
      align-items: center;
      gap: 0.55rem;
      min-height: 34px;
      padding: 0.45rem 0.7rem 0.45rem 0.55rem;
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.04);
      border: 1px solid rgba(255, 255, 255, 0.08);
      color: rgba(246, 239, 229, 0.72);
      font-size: 0.78rem;
      line-height: 1.2;
      font-family: Arial, Helvetica, sans-serif;
    }

    .trophy-icon {
      position: relative;
      width: 16px;
      height: 14px;
      border: 1.6px solid rgba(242, 193, 78, 0.92);
      border-bottom: 0;
      border-radius: 0 0 7px 7px;
      transform: translateY(-1px);
      flex: 0 0 auto;
    }

    .trophy-icon::before,
    .trophy-icon::after {
      content: "";
      position: absolute;
      top: 1px;
      width: 5px;
      height: 5px;
      border: 1.4px solid rgba(242, 193, 78, 0.92);
      border-bottom: 0;
      border-radius: 999px 999px 0 0;
    }

    .trophy-icon::before {
      left: -5px;
      border-right: 0;
    }

    .trophy-icon::after {
      right: -5px;
      border-left: 0;
    }

    .trophy-stem {
      position: relative;
      width: 2px;
      height: 6px;
      background: rgba(242, 193, 78, 0.92);
      flex: 0 0 auto;
      margin-left: -0.35rem;
      margin-right: -0.2rem;
    }

    .trophy-stem::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: -3px;
      width: 10px;
      height: 2px;
      background: rgba(242, 193, 78, 0.92);
      transform: translateX(-50%);
      border-radius: 999px;
    }

    .player-stats-note {
      margin-top: 1rem;
      font-size: 0.86rem;
      line-height: 1.65;
      color: rgba(246, 239, 229, 0.56);
      font-family: Arial, Helvetica, sans-serif;
    }

    .player-spotlight-panel .panel-side {
      align-self: start;
      justify-items: end;
      backface-visibility: hidden;
      transform: translateZ(0);
      will-change: transform, opacity;
    }

    .player-spotlight-panel .panel-side.is-fixed {
      position: fixed;
      bottom: 0;
      right: var(--player-side-right, 5.6vw);
      width: var(--maradona-side-width, 480px);
      display: grid;
      align-items: end;
      justify-items: end;
      z-index: 6;
    }

    .player-spotlight-panel .panel-side.is-bottom {
      position: absolute;
      right: var(--player-side-right, 5.6vw);
      bottom: 0;
      width: var(--maradona-side-width, 480px);
      display: grid;
      align-items: end;
      justify-items: end;
      z-index: 2;
    }

    .player-spotlight-panel .panel-side.is-fade-fixed {
      position: fixed;
      bottom: 0;
      right: var(--player-side-right, 5.6vw);
      width: var(--maradona-side-width, 480px);
      display: grid;
      align-items: end;
      justify-items: end;
      z-index: 6;
    }

    .player-portrait-wrap {
      position: relative;
      width: min(46vw, 680px);
      height: auto;
      overflow: hidden;
      display: grid;
      align-items: end;
      transform:
        translateZ(0)
        translateX(calc((1 - var(--player-enter-progress)) * 180px))
        translateY(calc((1 - var(--player-enter-progress)) * 12px));
      backface-visibility: hidden;
      will-change: transform, opacity;
    }

    .player-name-overlay {
      position: absolute;
      top: 1.2rem;
      left: -0.02em;
      z-index: 3;
      pointer-events: none;
      font-size: clamp(3.4rem, 7vw, 6.1rem);
      line-height: 0.84;
      letter-spacing: -0.07em;
      text-transform: uppercase;
      color: rgba(255, 247, 229, 0.9);
      text-shadow: 0 18px 36px rgba(0, 0, 0, 0.2);
      mix-blend-mode: screen;
    }

    .player-name-overlay span {
      display: block;
    }

    .player-name-overlay .outline {
      color: transparent;
      -webkit-text-stroke: 1px rgba(255, 247, 229, 0.38);
      text-stroke: 1px rgba(255, 247, 229, 0.38);
      opacity: 0.8;
    }

    .player-portrait-wrap::before {
      display: none;
    }

    .player-portrait-wrap::after {
      content: "";
      position: absolute;
      inset: auto 0 0 auto;
      width: 82%;
      height: 18%;
      background: radial-gradient(circle, rgba(0, 0, 0, 0.24), transparent 72%);
      filter: blur(18px);
      opacity: 0.72;
      pointer-events: none;
      z-index: 0;
    }

    .player-flag-layer {
      position: absolute;
      inset: 6% 2% 10% 2%;
      border-radius: 36px;
      overflow: hidden;
      opacity: 0.42;
      filter: saturate(0.92) brightness(0.92);
      box-shadow:
        inset 0 1px 0 rgba(255, 255, 255, 0.04),
        0 20px 40px rgba(0, 0, 0, 0.12);
      pointer-events: none;
      z-index: 0;
    }

    .player-flag-layer img {
      display: block;
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: center;
    }

    .player-portrait {
      position: relative;
      z-index: 1;
      display: block;
      width: 100%;
      height: min(92vh, 980px);
      object-fit: contain;
      object-position: right bottom;
      transform: translateZ(0);
      backface-visibility: hidden;
      filter: drop-shadow(0 36px 52px rgba(0, 0, 0, 0.28));
    }

    .panel-index {
      font-size: 0.78rem;
      color: rgba(246, 239, 229, 0.62);
      margin-bottom: 1rem;
    }

    .section-signature .panel-index,
    .contribution-signature .panel-index,
    .closing-signature .panel-index {
      position: relative;
      display: flex;
      align-items: center;
      gap: 1.75rem;
      margin-bottom: 0.7rem;
      color: rgba(242, 193, 78, 0.88);
    }

    .section-signature .panel-index::before,
    .contribution-signature .panel-index::before,
    .closing-signature .panel-index::before {
      content: "";
      width: 42px;
      height: 52px;
      flex: 0 0 auto;
      background: center / contain no-repeat url("/Users/eddy/Desktop/Barca 10/Barca Gold.png");
      filter: none;
      opacity: 1;
    }

    .section-signature .panel-index::after,
    .contribution-signature .panel-index::after,
    .closing-signature .panel-index::after {
      content: "";
      position: absolute;
      left: calc(42px + 0.9rem);
      top: 50%;
      width: 1px;
      height: 3.2rem;
      background: rgba(242, 193, 78, 0.62);
      transform: translateY(-50%);
    }

    .headline-rule {
      width: min(36vw, 380px);
      height: 7px;
      border-radius: 999px;
      margin-bottom: 1.25rem;
      background: linear-gradient(90deg, var(--gold), rgba(242, 193, 78, 0.15));
      transform-origin: left center;
    }

    .section-signature .headline-rule,
    .contribution-signature .headline-rule,
    .closing-signature .headline-rule {
      width: min(92%, 760px);
      height: 1px;
      margin-bottom: 1.6rem;
      border-radius: 0;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.86), rgba(242, 193, 78, 0.16));
    }

    .panel h2 {
      margin: 0 0 1rem;
      font-size: clamp(2.4rem, 5vw, 5rem);
      line-height: 0.92;
      max-width: 8.5ch;
    }

    .lede {
      margin: 0 0 1.25rem;
      max-width: 34rem;
      font-size: clamp(1rem, 1.2vw, 1.1rem);
      line-height: 1.75;
      color: rgba(246, 239, 229, 0.92);
      font-family: Arial, Helvetica, sans-serif;
    }

    .detail {
      max-width: 34rem;
      font-size: 0.98rem;
      line-height: 1.8;
      color: rgba(246, 239, 229, 0.74);
      font-family: Arial, Helvetica, sans-serif;
    }

    .panel-side {
      display: grid;
      gap: 1rem;
    }

    .stat-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 1rem;
    }

    .stat-card,
    .quote-card,
    .diagram-card {
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 24px;
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(10px);
      box-shadow: 0 20px 50px rgba(0, 0, 0, 0.18);
    }

    .panel:nth-child(1) .diagram-card {
      background: rgba(10, 16, 28, 0.72);
      border-color: rgba(255, 255, 255, 0.12);
      backdrop-filter: blur(6px);
      box-shadow: 0 24px 60px rgba(0, 0, 0, 0.16);
    }

    .stat-card {
      padding: 1rem 1.1rem 1.15rem;
      min-height: 128px;
    }

    .micro-label {
      font-size: 0.68rem;
      color: rgba(246, 239, 229, 0.58);
      margin-bottom: 0.6rem;
    }

    .stat-value {
      font-size: clamp(1.8rem, 2.8vw, 3rem);
      line-height: 0.95;
    }

    .stat-copy {
      margin-top: 0.5rem;
      font-size: 0.93rem;
      line-height: 1.55;
      color: rgba(246, 239, 229, 0.76);
      font-family: Arial, Helvetica, sans-serif;
    }

    .diagram-card {
      padding: 1.2rem;
    }

    .palette-stack {
      display: grid;
      gap: 1rem;
    }

    .palette-row {
      display: grid;
      grid-template-columns: 160px 1fr;
      border-radius: 22px;
      overflow: hidden;
      border: 1px solid rgba(255, 255, 255, 0.1);
      background: rgba(255, 255, 255, 0.03);
    }

    .swatch {
      min-height: 104px;
    }

    .swatch-copy {
      padding: 1rem 1.1rem;
      font-family: Arial, Helvetica, sans-serif;
    }

    .swatch-name {
      font-size: 1.1rem;
      font-weight: 700;
      margin-bottom: 0.35rem;
    }

    .swatch-meta {
      font-size: 0.82rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.56);
      margin-bottom: 0.55rem;
    }

    .swatch-note {
      line-height: 1.6;
      color: rgba(246, 239, 229, 0.78);
      font-size: 0.93rem;
    }

    .kit-gallery {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 0.9rem;
    }

    .kit-card {
      padding: 1rem 0.85rem 0.9rem;
      border-radius: 22px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      background: rgba(10, 16, 28, 0.52);
      text-align: center;
      font-family: Arial, Helvetica, sans-serif;
    }

    .kit-shirt {
      width: 84px;
      height: 92px;
      margin: 0 auto 0.85rem;
      clip-path: polygon(20% 0%, 36% 0%, 43% 12%, 57% 12%, 64% 0%, 80% 0%, 100% 20%, 84% 32%, 84% 100%, 16% 100%, 16% 32%, 0% 20%);
      border: 1px solid rgba(255, 255, 255, 0.18);
      box-shadow: inset 0 0 0 1px rgba(0, 0, 0, 0.12);
    }

    .kit-era {
      font-size: 0.74rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.6);
      margin-bottom: 0.35rem;
    }

    .kit-name {
      font-size: 0.94rem;
      line-height: 1.45;
      color: rgba(246, 239, 229, 0.86);
    }

    .kit-archive-panel {
      --archive-exit-progress: 0;
      min-height: 100vh;
      display: block;
      padding-top: 4.5vw;
      padding-bottom: 7vw;
      background: transparent;
      overflow: visible;
    }

    .kit-archive-panel::before {
      content: "";
      position: absolute;
      inset: 0;
      background: var(--archive-shared-bg);
      background-size: 100% 100%, 100% 100%, 100% 100%;
      background-repeat: no-repeat, no-repeat, no-repeat;
      background-position: 0 0, 0 0, 0 0;
      pointer-events: none;
      z-index: 0;
    }

    .kit-archive-panel::after {
      content: "";
      position: absolute;
      left: 0;
      top: 0;
      bottom: 0;
      width: 56%;
      background: repeating-linear-gradient(
        90deg,
        rgba(255, 255, 255, 0.044) 0,
        rgba(255, 255, 255, 0.044) 1px,
        transparent 1px,
        transparent 8.3vw
      );
      pointer-events: none;
      z-index: 0;
    }

    .kit-archive-panel {
      --kit-preview-pin-top: 7.6vh;
      --kit-rail-pin-top: 9vh;
    }

    .kit-archive-layout {
      display: grid;
      grid-template-columns: minmax(0, 1.05fr) minmax(0, 0.95fr);
      gap: 3vw;
      align-items: stretch;
      min-height: 100%;
      position: relative;
      z-index: 1;
    }

    .kit-preview-column {
      min-height: 100%;
      min-width: 0;
      align-self: stretch;
      position: relative;
      display: grid;
      align-items: start;
    }

    .kit-timeline-column {
      min-height: 100%;
      min-width: 0;
      align-self: stretch;
      position: relative;
      padding-right: 2.8vw;
    }

    .kit-preview-sticky {
      position: sticky;
      top: var(--kit-preview-pin-top);
      width: min(100%, 44rem);
      opacity: calc(1 - var(--archive-exit-progress, 0));
      transform: translateY(calc(var(--archive-exit-progress, 0) * -28px));
      transition: transform 220ms ease, opacity 220ms ease;
    }

    .kit-preview-sticky.is-floating {
      position: fixed;
      top: var(--kit-preview-pin-top);
      left: var(--kit-preview-left, 0px);
      width: min(var(--kit-preview-width, 704px), 44rem);
      z-index: 8;
    }

    .kit-preview-sticky.is-bottom {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 7vw;
      top: auto;
      width: 100%;
      z-index: 2;
    }

    .kit-preview-card {
      margin-top: 0;
      padding: 0;
      border-radius: 0;
      border: 0;
      background: transparent;
      backdrop-filter: none;
      box-shadow: none;
      display: grid;
      align-items: start;
      position: relative;
      min-height: 76vh;
    }

    .kit-preview-sticky > h2 {
      font-family: "Satoshi Black", "Satoshi-Black", "Satoshi", "Helvetica Neue", Arial, Helvetica, sans-serif;
      max-width: 11ch;
      margin-bottom: 0.55rem;
      font-size: clamp(2.1rem, 4.25vw, 4.15rem);
    }

    .kit-preview-sticky .panel-index {
      margin-bottom: 0.38rem;
      color: rgba(242, 193, 78, 0.9);
      letter-spacing: 0.18em;
    }

    .kit-preview-sticky .headline-rule {
      position: static;
    }

    .kit-preview-sticky .headline-rule::after {
      content: none;
    }

    .kit-preview-header {
      display: grid;
      order: 2;
      gap: 0.35rem;
      justify-items: start;
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      position: absolute;
      left: 0;
      bottom: 10.4rem;
      z-index: 3;
    }

    .kit-preview-season {
      position: relative;
      font-size: clamp(1.85rem, 2.9vw, 3rem);
      font-weight: 700;
      line-height: 0.95;
      letter-spacing: -0.04em;
      color: rgba(246, 239, 229, 0.96);
      padding-top: 1.15rem;
    }

    .kit-preview-season::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 2.1rem;
      height: 2px;
      border-radius: 999px;
      background: var(--gold);
    }

    .kit-preview-tag {
      font-size: 0.72rem;
      letter-spacing: 0.28em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.8);
    }

    .kit-stage {
      order: 1;
      min-height: 405px;
      display: grid;
      place-items: center;
      border-radius: 0;
      background: transparent;
      border: 0;
      margin-bottom: 0.8rem;
      justify-items: start;
      align-items: end;
      position: relative;
      isolation: isolate;
    }

    .kit-stage::before {
      content: "";
      position: absolute;
      left: clamp(0.5rem, 5vw, 5.5rem);
      bottom: 1.1rem;
      width: min(37vw, 530px);
      height: min(22vw, 275px);
      background:
        radial-gradient(circle at 30% 56%, rgba(165, 0, 68, 0.58), transparent 60%),
        radial-gradient(circle at 72% 44%, rgba(0, 77, 152, 0.58), transparent 62%),
        radial-gradient(circle at 50% 58%, rgba(242, 193, 78, 0.12), transparent 58%);
      filter: blur(38px);
      opacity: 0.92;
      transform: rotate(-2deg);
      pointer-events: none;
      z-index: 0;
      animation: kitGlowDrift 7.5s ease-in-out infinite alternate;
    }

    @keyframes kitGlowDrift {
      0% {
        opacity: 0.76;
        transform: translate3d(-1.2%, 1.5%, 0) scale(0.96) rotate(-3deg);
        filter: blur(40px) saturate(1.05);
      }
      50% {
        opacity: 0.98;
        transform: translate3d(1.5%, -1%, 0) scale(1.04) rotate(-1deg);
        filter: blur(34px) saturate(1.22);
      }
      100% {
        opacity: 0.86;
        transform: translate3d(2.2%, 1%, 0) scale(1.01) rotate(1deg);
        filter: blur(42px) saturate(1.14);
      }
    }

    .archive-shirt-photo {
      display: none;
      width: min(38vw, 545px);
      max-height: 430px;
      object-fit: contain;
      filter: drop-shadow(0 24px 42px rgba(0, 0, 0, 0.32));
      margin-left: clamp(2rem, 7vw, 8rem);
      margin-bottom: -1.2rem;
      position: relative;
      z-index: 1;
    }

    .archive-shirt-photo.is-visible {
      display: block;
    }

    .archive-shirt-photo.is-heritage {
      width: min(35vw, 500px);
      max-height: 398px;
    }

    .archive-shirt-photo.is-compact {
      width: min(35.8vw, 510px);
      max-height: 405px;
    }

    .archive-shirt {
      width: min(30vw, 360px);
      aspect-ratio: 0.92 / 1;
      clip-path: polygon(20% 0%, 36% 0%, 43% 12%, 57% 12%, 64% 0%, 80% 0%, 100% 20%, 84% 32%, 84% 100%, 16% 100%, 16% 32%, 0% 20%);
      border: 1px solid rgba(255, 255, 255, 0.18);
      box-shadow:
        inset 0 0 0 1px rgba(255, 255, 255, 0.06),
        0 18px 40px rgba(0, 0, 0, 0.22);
      position: relative;
      overflow: hidden;
      background: #004d98;
      transition: background 220ms ease, transform 220ms ease;
      margin-left: clamp(2rem, 7vw, 8rem);
      margin-bottom: -1.2rem;
      z-index: 1;
    }

    .archive-shirt::before {
      content: "";
      position: absolute;
      inset: 0;
      background: linear-gradient(180deg, rgba(255, 255, 255, 0.06), transparent 25%);
      pointer-events: none;
    }

    .archive-shirt::after {
      content: "";
      position: absolute;
      top: 11%;
      left: 50%;
      width: 18%;
      height: 10%;
      transform: translateX(-50%);
      border-radius: 0 0 10px 10px;
      background: rgba(7, 17, 31, 0.42);
      pointer-events: none;
    }

    .kit-preview-note {
      display: block;
      order: 3;
      max-width: 20rem;
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.66);
      font-size: 0.98rem;
      line-height: 1.65;
      position: absolute;
      left: 0;
      bottom: 5.9rem;
      z-index: 3;
    }

    .kit-preview-meta {
      display: none;
      order: 4;
      width: fit-content;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.62rem;
      letter-spacing: 0.28em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.82);
      position: absolute;
      left: 0;
      bottom: 1.8rem;
      z-index: 3;
    }

    .kit-preview-meta::after {
      content: " ->";
      letter-spacing: 0.08em;
    }

    .kit-season-list {
      display: grid;
      gap: 0.15rem;
      padding-left: 6px;
      padding-right: 2px;
      padding-top: 19vh;
      padding-bottom: 36vh;
      transition: transform 240ms ease;
      will-change: transform;
    }

    .kit-timeline-rail {
      position: sticky;
      top: var(--kit-rail-pin-top);
      width: var(--kit-timeline-width, 100%);
      height: 86vh;
      overflow: hidden;
      z-index: 2;
      opacity: calc(1 - var(--archive-exit-progress, 0));
      transform: translateY(calc(var(--archive-exit-progress, 0) * -22px));
      transition: transform 220ms ease, opacity 220ms ease;
      mask-image: linear-gradient(180deg, transparent 0%, rgba(0,0,0,1) 12%, rgba(0,0,0,1) 88%, transparent 100%);
      -webkit-mask-image: linear-gradient(180deg, transparent 0%, rgba(0,0,0,1) 12%, rgba(0,0,0,1) 88%, transparent 100%);
    }

    .kit-timeline-rail.is-floating {
      position: fixed;
      top: var(--kit-rail-pin-top);
      left: var(--kit-timeline-left, 0px);
      width: var(--kit-timeline-width, 100%);
      height: 86vh;
      overflow: hidden;
      z-index: 8;
      mask-image: linear-gradient(180deg, transparent 0%, rgba(0,0,0,1) 12%, rgba(0,0,0,1) 88%, transparent 100%);
      -webkit-mask-image: linear-gradient(180deg, transparent 0%, rgba(0,0,0,1) 12%, rgba(0,0,0,1) 88%, transparent 100%);
    }

    .kit-timeline-rail.is-bottom {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 3.6vw;
      top: auto;
      width: var(--kit-timeline-width, 100%);
      height: 86vh;
      overflow: hidden;
      z-index: 2;
      mask-image: linear-gradient(180deg, transparent 0%, rgba(0,0,0,1) 12%, rgba(0,0,0,1) 88%, transparent 100%);
      -webkit-mask-image: linear-gradient(180deg, transparent 0%, rgba(0,0,0,1) 12%, rgba(0,0,0,1) 88%, transparent 100%);
    }

    .kit-season-step {
      display: grid;
      grid-template-columns: 34px 1fr;
      gap: 1rem;
      align-items: center;
      position: relative;
      isolation: isolate;
      min-height: 62px;
      padding: 0.55rem 0;
      font-family: "Helvetica Neue", Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.46);
      transition: color 180ms ease;
      cursor: pointer;
    }

    .kit-season-step:focus-visible {
      outline: 1px solid rgba(242, 193, 78, 0.55);
      outline-offset: 6px;
      border-radius: 10px;
    }

    .kit-season-step::after {
      content: "";
      position: absolute;
      left: calc(34px + 1rem + 2px);
      right: -2.8vw;
      bottom: 0;
      height: 1px;
      background: rgba(255, 255, 255, 0.06);
      z-index: 0;
    }

    .kit-season-dot {
      position: relative;
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.16);
      box-shadow: none;
      transition: background 180ms ease, transform 180ms ease;
      justify-self: center;
      z-index: 1;
    }

    .kit-season-dot::before {
      content: "";
      position: absolute;
      inset: -10px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.03);
      transition: background 180ms ease, transform 180ms ease;
      z-index: -1;
    }

    .kit-season-label {
      display: flex;
      align-items: baseline;
      justify-content: space-between;
      gap: 1.2rem;
      padding-bottom: 0.7rem;
    }

    .kit-season-year {
      font-family: "Inter", "Helvetica Neue", Arial, Helvetica, sans-serif;
      font-size: 0.96rem;
      font-weight: 500;
      letter-spacing: 0.01em;
      color: rgba(246, 239, 229, 0.78);
    }

    .kit-season-style {
      font-family: "Inter", "Helvetica Neue", Arial, Helvetica, sans-serif;
      font-size: 0.72rem;
      font-weight: 500;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.36);
    }

    .kit-season-step.is-active {
      color: rgba(246, 239, 229, 0.92);
    }

    .kit-season-step.is-active .kit-season-dot {
      background: var(--gold);
      transform: scale(1.15);
    }

    .kit-season-step.is-active .kit-season-dot::before {
      background: rgba(242, 193, 78, 0.14);
      transform: scale(1.02);
    }

    .kit-season-step.is-active .kit-season-year {
      color: rgba(246, 239, 229, 0.96);
    }

    .kit-season-step.is-active .kit-season-style {
      color: rgba(242, 193, 78, 0.88);
    }

    .timeline {
      display: grid;
      gap: 0.85rem;
    }

    .timeline-row {
      display: grid;
      grid-template-columns: 72px 1fr;
      gap: 0.9rem;
      align-items: start;
      font-family: Arial, Helvetica, sans-serif;
    }

    .timeline-year {
      color: var(--gold);
      font-size: 0.84rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      padding-top: 0.15rem;
    }

    .timeline-copy {
      color: rgba(246, 239, 229, 0.82);
      line-height: 1.6;
      border-left: 1px solid rgba(255, 255, 255, 0.12);
      padding-left: 0.9rem;
    }

    .quote-card {
      padding: 1.2rem 1.3rem;
      font-family: Arial, Helvetica, sans-serif;
    }

    .quote-mark {
      color: var(--gold);
      font-size: 2.1rem;
      line-height: 1;
      margin-bottom: 0.4rem;
    }

    .quote-text {
      line-height: 1.75;
      color: rgba(246, 239, 229, 0.88);
      margin: 0;
    }

    .quote-source {
      margin-top: 0.9rem;
      color: rgba(246, 239, 229, 0.58);
      font-size: 0.85rem;
      letter-spacing: 0.04em;
      text-transform: uppercase;
    }

    .pass-map {
      position: relative;
      aspect-ratio: 1.15 / 1;
      border-radius: 24px;
      overflow: hidden;
      border: 1px solid rgba(255, 255, 255, 0.12);
      background:
        radial-gradient(circle at center, rgba(242, 193, 78, 0.12), transparent 42%),
        linear-gradient(180deg, rgba(255, 255, 255, 0.04), rgba(255, 255, 255, 0.02));
    }

    .pitch-line {
      position: absolute;
      border-color: rgba(255, 255, 255, 0.18);
      border-style: solid;
    }

    .pitch-outer {
      inset: 8%;
      border-width: 1px;
    }

    .pitch-half {
      top: 8%;
      bottom: 8%;
      left: 50%;
      border-left-width: 1px;
    }

    .pitch-circle {
      top: 50%;
      left: 50%;
      width: 22%;
      height: 22%;
      border-width: 1px;
      border-radius: 50%;
      transform: translate(-50%, -50%);
    }

    .node,
    .edge {
      position: absolute;
      transform-origin: center;
    }

    .node {
      width: 14px;
      height: 14px;
      border-radius: 50%;
      background: var(--gold);
      box-shadow: 0 0 0 6px rgba(242, 193, 78, 0.14);
    }

    .edge {
      height: 2px;
      background: linear-gradient(90deg, rgba(242, 193, 78, 0.1), rgba(242, 193, 78, 0.9));
      opacity: 0.84;
    }

    .bars {
      display: flex;
      align-items: end;
      gap: 0.8rem;
      min-height: 176px;
      padding-top: 0.8rem;
    }

    .bar-col {
      flex: 1;
      min-width: 0;
    }

    .bar-label {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.72rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.62);
      margin-top: 0.65rem;
    }

    .bar-track {
      height: 150px;
      display: flex;
      align-items: end;
    }

    .bar-fill {
      width: 100%;
      border-radius: 14px 14px 4px 4px;
      background: linear-gradient(180deg, var(--gold), #df9f14);
      transform-origin: bottom center;
      box-shadow: 0 10px 30px rgba(242, 193, 78, 0.18);
    }

    .closing {
      min-height: 100vh;
      padding: 7vw;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
      align-items: center;
      background: var(--crest-section-bg);
    }

    .closing-signature {
      margin-bottom: 1.5rem;
    }

    .closing h3 {
      margin: 0 0 1rem;
      font-size: clamp(2.2rem, 4vw, 4rem);
      line-height: 0.95;
      max-width: 10ch;
    }

    .closing p {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: var(--muted);
      line-height: 1.8;
      max-width: 40rem;
    }

    .closing-card {
      padding: 2rem;
      border-radius: 28px;
      border: 1px solid var(--line);
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.04), rgba(255, 255, 255, 0.02)),
        linear-gradient(135deg, rgba(0, 77, 152, 0.18), rgba(165, 0, 68, 0.14));
    }

    .contribution-section {
      min-height: 100vh;
      padding: 7vw;
      background: var(--deep-section-bg);
    }

    .contribution-head {
      display: grid;
      grid-template-columns: minmax(0, 30rem) minmax(0, 1fr);
      gap: 2rem;
      align-items: end;
      margin-bottom: 2rem;
    }

    .contribution-signature {
      margin-bottom: 1.5rem;
    }

    .contribution-head h3 {
      margin: 0;
      font-size: clamp(2.5rem, 5vw, 5rem);
      line-height: 0.92;
      max-width: 8ch;
    }

    .contribution-copy {
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.74);
      line-height: 1.75;
      max-width: 42rem;
    }

    .contribution-copy p {
      margin: 0;
    }

    .contribution-scale {
      margin-top: 1rem;
      font-size: 0.78rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(242, 193, 78, 0.78);
    }

    .contribution-grid {
      display: grid;
      grid-template-columns: repeat(6, minmax(0, 1fr));
      gap: 1rem;
      align-items: stretch;
    }

    .contribution-card {
      position: relative;
      min-height: 36rem;
      padding: 1.05rem 1rem 1rem;
      border-radius: 28px;
      border: 1px solid rgba(255, 255, 255, 0.08);
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.06), rgba(255, 255, 255, 0.02)),
        rgba(7, 17, 31, 0.82);
      overflow: hidden;
      box-shadow: 0 30px 80px rgba(0, 0, 0, 0.24);
    }

    .contribution-card::before {
      content: "";
      position: absolute;
      inset: 0;
      background: linear-gradient(180deg, rgba(242, 193, 78, 0.08), transparent 28%);
      pointer-events: none;
    }

    .contribution-player,
    .contribution-total,
    .contribution-breakdown {
      position: relative;
      z-index: 1;
    }

    .contribution-player {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.8rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.62);
    }

    .contribution-total {
      margin-top: 0.4rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: clamp(2.2rem, 4vw, 3.4rem);
      font-weight: 700;
      letter-spacing: -0.08em;
      color: rgba(246, 239, 229, 0.98);
      line-height: 0.9;
    }

    .contribution-breakdown {
      margin-top: 0.35rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.76rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: rgba(246, 239, 229, 0.48);
    }

    .ball-rain {
      position: relative;
      height: 26rem;
      margin-top: 1.2rem;
      border-radius: 22px;
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.04), rgba(255, 255, 255, 0.015)),
        rgba(5, 12, 22, 0.86);
      border: 1px solid rgba(255, 255, 255, 0.06);
      overflow: hidden;
    }

    .ball-rain::before {
      content: "";
      position: absolute;
      left: 12%;
      right: 12%;
      top: 0;
      bottom: 0;
      background-image:
        linear-gradient(rgba(255, 255, 255, 0.06) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255, 255, 255, 0.04) 1px, transparent 1px);
      background-size: 24px 24px;
      mask-image: linear-gradient(180deg, rgba(0, 0, 0, 0.18), rgba(0, 0, 0, 0.78));
      pointer-events: none;
    }

    .ball-rain-bin {
      position: absolute;
      left: 0.9rem;
      right: 0.9rem;
      bottom: 0.9rem;
      min-height: 4.6rem;
      padding: 0.7rem 0.6rem 0.85rem;
      border-radius: 18px;
      border: 1px solid rgba(255, 255, 255, 0.08);
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.06), rgba(255, 255, 255, 0.02)),
        rgba(10, 21, 37, 0.96);
      display: flex;
      flex-wrap: wrap;
      align-content: flex-end;
      gap: 0.2rem;
      justify-content: center;
    }

    .rain-ball {
      position: absolute;
      top: -2rem;
      left: var(--x, 50%);
      width: 19px;
      height: 19px;
      border-radius: 50%;
      background:
        radial-gradient(circle at 34% 32%, rgba(255, 255, 255, 0.95), rgba(255, 255, 255, 0.22) 22%, transparent 24%),
        radial-gradient(circle at 30% 30%, #fff2c8, #f2c14e 55%, #d79c17 100%);
      box-shadow:
        inset -3px -4px 6px rgba(0, 0, 0, 0.22),
        0 6px 20px rgba(242, 193, 78, 0.28);
      animation: ball-drop var(--duration, 5.5s) linear infinite;
      animation-delay: var(--delay, 0s);
    }

    .bin-ball {
      width: 14px;
      height: 14px;
      border-radius: 50%;
      background:
        radial-gradient(circle at 32% 28%, rgba(255, 255, 255, 0.95), rgba(255, 255, 255, 0.16) 22%, transparent 24%),
        radial-gradient(circle at 30% 30%, #fff2c8, #f2c14e 58%, #d79c17 100%);
      box-shadow: inset -2px -2px 4px rgba(0, 0, 0, 0.2);
    }

    .trophy-scatter-block {
      margin-top: 3.2rem;
      border-radius: 28px;
      border: 1px solid rgba(246, 239, 229, 0.12);
      background:
        radial-gradient(circle at 18% 22%, rgba(165, 0, 68, 0.18), transparent 28rem),
        radial-gradient(circle at 86% 72%, rgba(0, 77, 152, 0.2), transparent 30rem),
        linear-gradient(180deg, rgba(255, 255, 255, 0.055), rgba(255, 255, 255, 0.018)),
        rgba(7, 17, 31, 0.9);
      box-shadow: 0 32px 100px rgba(0, 0, 0, 0.28);
      overflow: hidden;
    }

    .trophy-scatter-head {
      display: grid;
      grid-template-columns: minmax(0, 28rem) minmax(0, 1fr);
      gap: 2rem;
      align-items: end;
      padding: 1.55rem 1.55rem 0;
    }

    .trophy-scatter-kicker,
    .trophy-scatter-copy,
    .trophy-axis-label,
    .trophy-gridline em,
    .trophy-point-label,
    .trophy-player-chip,
    .trophy-detail-kicker,
    .trophy-detail-era,
    .trophy-detail-stat span,
    .trophy-detail-note {
      font-family: Arial, Helvetica, sans-serif;
    }

    .trophy-scatter-kicker {
      margin-bottom: 0.65rem;
      color: rgba(242, 193, 78, 0.78);
      font-size: 0.74rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
    }

    .trophy-scatter-head h4 {
      margin: 0;
      max-width: 13ch;
      font-size: clamp(2.1rem, 4.5vw, 4.4rem);
      line-height: 0.94;
    }

    .trophy-scatter-copy {
      margin: 0;
      max-width: 42rem;
      color: rgba(246, 239, 229, 0.68);
      line-height: 1.7;
    }

    .trophy-scatter-layout {
      display: grid;
      grid-template-columns: minmax(0, 1fr) minmax(19rem, 0.38fr);
      gap: 1.25rem;
      align-items: stretch;
      padding: 1.35rem 1.55rem 1.55rem;
    }

    .trophy-scatter-plot {
      position: relative;
      min-height: 560px;
      border-radius: 24px;
      border: 1px solid rgba(255, 255, 255, 0.08);
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.04), rgba(255, 255, 255, 0.012)),
        rgba(3, 10, 20, 0.72);
      overflow: hidden;
      --focus-x: 0%;
      --focus-y: 0%;
    }

    .trophy-scatter-plot::before {
      content: "";
      position: absolute;
      inset: 0;
      background-image:
        linear-gradient(rgba(246, 239, 229, 0.035) 1px, transparent 1px),
        linear-gradient(90deg, rgba(246, 239, 229, 0.03) 1px, transparent 1px);
      background-size: 36px 36px;
      pointer-events: none;
      mask-image: linear-gradient(180deg, rgba(0, 0, 0, 0.9), rgba(0, 0, 0, 0.38));
    }

    .trophy-plot-area {
      position: absolute;
      inset: 2.15rem 1.35rem 4.25rem 4.75rem;
    }

    .trophy-gridline {
      position: absolute;
      background: rgba(246, 239, 229, 0.09);
      pointer-events: none;
    }

    .trophy-gridline.is-y {
      left: 0;
      right: 0;
      bottom: var(--offset);
      height: 1px;
    }

    .trophy-gridline.is-x {
      top: 0;
      bottom: 0;
      left: var(--offset);
      width: 1px;
    }

    .trophy-gridline em {
      position: absolute;
      color: rgba(246, 239, 229, 0.52);
      font-size: 0.68rem;
      font-style: normal;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }

    .trophy-gridline.is-y em {
      right: calc(100% + 0.72rem);
      top: -0.45rem;
      width: 2.3rem;
      text-align: right;
    }

    .trophy-gridline.is-x em {
      top: calc(100% + 0.68rem);
      left: 50%;
      transform: translateX(-50%);
    }

    .trophy-focus-line {
      position: absolute;
      z-index: 1;
      background: rgba(242, 193, 78, 0.32);
      pointer-events: none;
      opacity: 0.9;
    }

    .trophy-focus-line.is-x {
      top: 0;
      bottom: 0;
      left: var(--focus-x);
      width: 1px;
    }

    .trophy-focus-line.is-y {
      left: 0;
      right: 0;
      bottom: var(--focus-y);
      height: 1px;
    }

    .trophy-scatter-points {
      position: absolute;
      inset: 0;
      z-index: 2;
    }

    .trophy-point {
      all: unset;
      position: absolute;
      left: var(--x);
      bottom: var(--y);
      width: var(--bubble-size);
      height: var(--bubble-size);
      transform: translate(-50%, 50%);
      border-radius: 999px;
      cursor: pointer;
      color: rgba(7, 17, 31, 0.95);
      background:
        radial-gradient(circle at 34% 28%, rgba(255, 255, 255, 0.92), rgba(255, 255, 255, 0.18) 24%, transparent 26%),
        linear-gradient(135deg, var(--accent), var(--accent-deep));
      box-shadow:
        0 0 0 1px rgba(255, 255, 255, 0.28),
        0 0 0 8px rgba(255, 255, 255, 0.04),
        0 18px 42px rgba(0, 0, 0, 0.3);
      display: grid;
      place-items: center;
      transition: transform 190ms ease, box-shadow 190ms ease, opacity 190ms ease;
    }

    .trophy-point span {
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.68rem;
      font-weight: 800;
      line-height: 1;
    }

    .trophy-point:not(.is-active) {
      opacity: 0.78;
    }

    .trophy-point:hover,
    .trophy-point:focus-visible,
    .trophy-point.is-active {
      opacity: 1;
      transform: translate(-50%, 50%) scale(1.18);
      box-shadow:
        0 0 0 1px rgba(246, 239, 229, 0.48),
        0 0 0 12px var(--accent-soft),
        0 22px 54px rgba(0, 0, 0, 0.36);
    }

    .trophy-point:focus-visible {
      outline: 2px solid rgba(242, 193, 78, 0.95);
      outline-offset: 5px;
    }

    .trophy-point-label {
      position: absolute;
      z-index: 3;
      left: var(--x);
      bottom: var(--y);
      transform: translate(calc(-50% + var(--label-x, 0px)), calc(100% + var(--label-y, 1.1rem)));
      padding: 0.34rem 0.48rem;
      border-radius: 999px;
      background: rgba(7, 17, 31, 0.88);
      border: 1px solid rgba(246, 239, 229, 0.12);
      color: rgba(246, 239, 229, 0.82);
      font-size: 0.66rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      white-space: nowrap;
      pointer-events: none;
      opacity: 0;
      transition: opacity 180ms ease, transform 180ms ease;
    }

    .trophy-point-label.is-active {
      opacity: 1;
      transform: translate(calc(-50% + var(--label-x, 0px)), calc(100% + var(--label-y, 1.1rem))) translateY(-0.2rem);
    }

    .trophy-axis-label {
      position: absolute;
      color: rgba(242, 193, 78, 0.72);
      font-size: 0.7rem;
      letter-spacing: 0.16em;
      text-transform: uppercase;
    }

    .trophy-axis-label.is-x {
      right: 1.35rem;
      bottom: 1.15rem;
    }

    .trophy-axis-label.is-y {
      left: 1.25rem;
      top: 1.2rem;
      writing-mode: vertical-rl;
      transform: rotate(180deg);
    }

    .trophy-detail-panel {
      position: relative;
      border-radius: 24px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.07), rgba(255, 255, 255, 0.025)),
        rgba(9, 19, 33, 0.92);
      padding: 1.35rem;
      min-height: 560px;
      overflow: hidden;
    }

    .trophy-detail-panel::before {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at 74% 12%, var(--active-soft, rgba(242, 193, 78, 0.18)), transparent 18rem);
      pointer-events: none;
    }

    .trophy-detail-panel > * {
      position: relative;
      z-index: 1;
    }

    .trophy-detail-kicker,
    .trophy-detail-era,
    .trophy-detail-note,
    .trophy-detail-stat span {
      text-transform: uppercase;
    }

    .trophy-detail-kicker {
      color: rgba(242, 193, 78, 0.72);
      font-size: 0.72rem;
      letter-spacing: 0.18em;
    }

    .trophy-detail-name {
      margin-top: 0.55rem;
      font-size: clamp(2.1rem, 4vw, 3.45rem);
      line-height: 0.94;
    }

    .trophy-detail-era {
      margin-top: 0.65rem;
      color: rgba(246, 239, 229, 0.52);
      font-size: 0.72rem;
      letter-spacing: 0.14em;
    }

    .trophy-detail-stats {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.85rem;
      margin-top: 1.35rem;
    }

    .trophy-detail-stat {
      padding-top: 0.75rem;
      border-top: 1px solid rgba(246, 239, 229, 0.14);
    }

    .trophy-detail-stat strong {
      display: block;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.98);
      font-size: 2.05rem;
      line-height: 1;
    }

    .trophy-detail-stat span {
      display: block;
      margin-top: 0.42rem;
      color: rgba(246, 239, 229, 0.48);
      font-size: 0.62rem;
      letter-spacing: 0.1em;
      line-height: 1.35;
    }

    .trophy-detail-copy {
      margin: 1.35rem 0 0;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.72);
      line-height: 1.65;
    }

    .trophy-detail-note {
      margin-top: 1rem;
      color: rgba(242, 193, 78, 0.7);
      font-size: 0.7rem;
      letter-spacing: 0.14em;
      line-height: 1.45;
    }

    .trophy-player-rail {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.55rem;
      margin-top: 1.25rem;
    }

    .trophy-player-chip {
      border: 1px solid rgba(246, 239, 229, 0.11);
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.035);
      color: rgba(246, 239, 229, 0.68);
      padding: 0.65rem 0.75rem;
      font-size: 0.68rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      cursor: pointer;
      transition: background 160ms ease, border-color 160ms ease, color 160ms ease;
    }

    .trophy-player-chip.is-active,
    .trophy-player-chip:hover,
    .trophy-player-chip:focus-visible {
      background: var(--active-soft, rgba(242, 193, 78, 0.16));
      border-color: var(--active, rgba(242, 193, 78, 0.7));
      color: rgba(246, 239, 229, 0.96);
    }

    @keyframes ball-drop {
      0% {
        transform: translate3d(0, 0, 0) scale(0.9);
        opacity: 0;
      }

      10% {
        opacity: 1;
      }

      86% {
        opacity: 1;
      }

      100% {
        transform: translate3d(0, 19.8rem, 0) scale(1.04);
        opacity: 0;
      }
    }

    .league-rank-section {
      position: relative;
      min-height: 340vh;
      overflow: visible;
      overflow: clip;
      background:
        radial-gradient(circle at 14% 22%, rgba(165, 0, 68, 0.18), transparent 30rem),
        radial-gradient(circle at 88% 76%, rgba(0, 77, 152, 0.2), transparent 32rem),
        var(--deep-section-bg);
      --rank-chart-scale: 1;
    }

    .league-rank-sticky {
      position: sticky;
      top: 0;
      height: 100vh;
      min-height: 720px;
      padding: 6vw;
      isolation: isolate;
    }

    .league-rank-backdrop {
      position: absolute;
      inset: 0;
      z-index: -1;
      background-image:
        linear-gradient(rgba(255, 255, 255, 0.035) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
      background-size: 52px 52px;
      mask-image: radial-gradient(circle at 42% 52%, rgba(0, 0, 0, 0.86), transparent 72%);
      pointer-events: none;
    }

    .league-rank-chart-shell {
      position: absolute;
      left: 50%;
      top: 50%;
      z-index: 1;
      width: min(82vw, 1120px);
      transform: translate(-50%, -50%) scale(var(--rank-chart-scale));
      transform-origin: center center;
    }

    .league-rank-signature {
      margin-bottom: 1.2rem;
    }

    .league-rank-chart-card {
      position: relative;
      display: grid;
      grid-template-columns: minmax(0, 1fr) minmax(17rem, 24rem);
      grid-template-areas:
        "head insight"
        "plot plot"
        "axis axis"
        "source source";
      column-gap: 1.35rem;
      row-gap: 1.15rem;
      border-radius: 28px;
      border: 1px solid rgba(246, 239, 229, 0.12);
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.055), rgba(255, 255, 255, 0.018)),
        rgba(7, 17, 31, 0.9);
      box-shadow: 0 32px 110px rgba(0, 0, 0, 0.34);
      padding: 1.4rem;
    }

    .league-rank-chart-top {
      grid-area: head;
      display: flex;
      justify-content: space-between;
      gap: 1.5rem;
      align-items: start;
      margin-bottom: 0;
    }

    .league-rank-kicker,
    .league-rank-source,
    .league-rank-data-label,
    .league-rank-era,
    .league-rank-fact span {
      font-family: Arial, Helvetica, sans-serif;
      text-transform: uppercase;
    }

    .league-rank-kicker {
      margin: 0 0 0.55rem;
      color: rgba(242, 193, 78, 0.78);
      font-size: 0.78rem;
      letter-spacing: 0.18em;
    }

    .league-rank-chart-top h3 {
      margin: 0;
      max-width: 11ch;
      font-size: 4rem;
      line-height: 0.94;
    }

    .league-rank-plot {
      grid-area: plot;
      position: relative;
      height: 390px;
      border-radius: 22px;
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.045), rgba(255, 255, 255, 0.015)),
        rgba(3, 10, 20, 0.74);
      border: 1px solid rgba(255, 255, 255, 0.07);
      overflow: hidden;
    }

    .league-rank-plot-area {
      position: absolute;
      inset: 1.55rem 1rem 3.1rem 3.8rem;
    }

    .league-rank-gridline {
      position: absolute;
      left: 0;
      right: 0;
      top: var(--line-top);
      height: 1px;
      background: rgba(246, 239, 229, 0.08);
    }

    .league-rank-gridline span {
      position: absolute;
      right: calc(100% + 0.7rem);
      top: -0.48rem;
      width: 2.3rem;
      text-align: right;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.5);
      font-size: 0.68rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }

    .league-rank-bars {
      position: absolute;
      inset: 0;
      display: grid;
      grid-template-columns: repeat(var(--rank-count), minmax(0, 1fr));
      align-items: end;
      gap: 0.24rem;
    }

    .league-rank-bar {
      all: unset;
      position: relative;
      height: 100%;
      min-width: 0;
      display: flex;
      align-items: end;
      cursor: pointer;
      --rank-accent: #73aaf4;
      --rank-accent-deep: var(--barca-blue);
      --rank-glow: rgba(80, 140, 215, 0.24);
    }

    .league-rank-bar:focus-visible {
      outline: 2px solid rgba(115, 170, 244, 0.95);
      outline-offset: 3px;
      border-radius: 8px;
    }

    .league-rank-bar-fill {
      width: 100%;
      height: var(--bar-height);
      min-height: 7px;
      border-radius: 8px 8px 2px 2px;
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.18), transparent 34%),
        linear-gradient(180deg, var(--rank-accent), var(--rank-accent-deep));
      box-shadow: 0 0 0 1px rgba(255, 255, 255, 0.08), 0 12px 28px var(--rank-glow);
      opacity: 0.78;
      transform-origin: bottom center;
      transition: opacity 180ms ease, transform 180ms ease, box-shadow 180ms ease;
    }

    .league-rank-bar.is-champion {
      --rank-accent: var(--gold);
      --rank-accent-deep: #d69b18;
      --rank-glow: rgba(242, 193, 78, 0.26);
    }

    .league-rank-bar.is-runner-up .league-rank-bar-fill {
      opacity: 0.82;
    }

    .league-rank-bar.is-runner-up {
      --rank-accent: #7fb8ff;
      --rank-accent-deep: var(--barca-blue);
      --rank-glow: rgba(80, 140, 215, 0.26);
    }

    .league-rank-bar.is-third-place {
      --rank-accent: #df547c;
      --rank-accent-deep: var(--barca-red);
      --rank-glow: rgba(165, 0, 68, 0.24);
    }

    .league-rank-bar.is-lower-finish {
      --rank-accent: #4e77b8;
      --rank-accent-deep: #213972;
      --rank-glow: rgba(35, 67, 126, 0.24);
    }

    .league-rank-bar.is-lower-finish .league-rank-bar-fill {
      opacity: 0.66;
    }

    .league-rank-bar:hover .league-rank-bar-fill,
    .league-rank-bar.is-active .league-rank-bar-fill {
      opacity: 1;
      transform: scaleX(1.28);
      box-shadow: 0 0 0 1px rgba(246, 239, 229, 0.35), 0 0 30px var(--rank-glow);
    }

    .league-rank-bar.is-active::before {
      content: "";
      position: absolute;
      left: 50%;
      bottom: calc(var(--bar-height) + 0.5rem);
      width: 0.55rem;
      height: 0.55rem;
      border-radius: 999px;
      background: var(--rank-accent);
      transform: translateX(-50%);
      box-shadow: 0 0 0 7px var(--rank-glow);
    }

    .league-rank-year {
      position: absolute;
      left: 50%;
      top: calc(100% + 0.64rem);
      transform: translateX(-50%);
      font-family: Arial, Helvetica, sans-serif;
      font-size: 0.64rem;
      letter-spacing: 0.06em;
      color: rgba(246, 239, 229, 0.48);
      white-space: nowrap;
      opacity: 0;
    }

    .league-rank-bar.is-decade .league-rank-year,
    .league-rank-bar.is-active .league-rank-year {
      opacity: 1;
    }

    .league-rank-axis-row {
      grid-area: axis;
      display: flex;
      justify-content: space-between;
      margin-top: -0.2rem;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.54);
      font-size: 0.72rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
    }

    .league-rank-source {
      grid-area: source;
      margin-top: -0.35rem;
      color: rgba(246, 239, 229, 0.42);
      font-size: 0.68rem;
      letter-spacing: 0.1em;
    }

    .league-rank-insights {
      grid-area: insight;
      position: relative;
      justify-self: end;
      align-self: start;
      z-index: 3;
      width: min(100%, 24rem);
      padding: 1.05rem;
      border-radius: 22px;
      border: 1px solid rgba(246, 239, 229, 0.15);
      background:
        linear-gradient(180deg, rgba(255, 255, 255, 0.08), rgba(255, 255, 255, 0.025)),
        rgba(9, 19, 33, 0.94);
      box-shadow: 0 22px 70px rgba(0, 0, 0, 0.28);
      opacity: 1;
    }

    .league-rank-data-label,
    .league-rank-era {
      color: rgba(242, 193, 78, 0.72);
      font-size: 0.74rem;
      letter-spacing: 0.18em;
    }

    .league-rank-season {
      margin-top: 0.45rem;
      font-family: Arial, Helvetica, sans-serif;
      font-size: clamp(2.25rem, 3vw, 3.15rem);
      font-weight: 800;
      line-height: 0.92;
      color: rgba(246, 239, 229, 0.98);
    }

    .league-rank-position {
      display: flex;
      align-items: baseline;
      gap: 0.65rem;
      margin-top: 0.55rem;
      padding-bottom: 0.8rem;
      border-bottom: 1px solid rgba(246, 239, 229, 0.12);
    }

    .league-rank-position strong {
      font-family: Arial, Helvetica, sans-serif;
      font-size: clamp(3.4rem, 4vw, 4.6rem);
      line-height: 0.84;
      color: #73aaf4;
    }

    .league-rank-section.is-rank-champion .league-rank-position strong {
      color: var(--gold);
    }

    .league-rank-section.is-rank-runner-up .league-rank-position strong {
      color: #7fb8ff;
    }

    .league-rank-section.is-rank-third-place .league-rank-position strong {
      color: #df547c;
    }

    .league-rank-section.is-rank-lower-finish .league-rank-position strong {
      color: #6f91d2;
    }

    .league-rank-position span {
      min-width: 0;
      flex: 1 1 auto;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.68);
      font-size: 0.95rem;
      line-height: 1.4;
    }

    .league-rank-detail {
      margin: 0.8rem 0 0.9rem;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.72);
      font-size: 0.9rem;
      line-height: 1.48;
    }

    .league-rank-facts {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 0.65rem;
      margin-top: 0.85rem;
    }

    .league-rank-fact {
      min-width: 0;
      padding-top: 0.75rem;
      border-top: 1px solid rgba(246, 239, 229, 0.14);
    }

    .league-rank-fact strong {
      display: block;
      font-family: Arial, Helvetica, sans-serif;
      color: rgba(246, 239, 229, 0.96);
      font-size: 1.35rem;
      line-height: 1;
    }

    .league-rank-fact span {
      display: block;
      margin-top: 0.42rem;
      color: rgba(246, 239, 229, 0.48);
      font-size: 0.62rem;
      letter-spacing: 0.1em;
      line-height: 1.35;
    }

    .league-rank-data-label,
    .league-rank-position span,
    .league-rank-detail,
    .league-rank-era,
    .league-rank-fact span {
      display: -webkit-box;
      -webkit-box-orient: vertical;
      -webkit-line-clamp: 2;
      overflow: hidden;
      text-overflow: ellipsis;
    }

    @media (max-width: 980px) {
      .hero,
      .panel,
      .closing,
      .contribution-head {
        grid-template-columns: 1fr;
      }

      .crest-archive-layout,
      .kit-archive-layout {
        grid-template-columns: 1fr;
      }

      .crest-preview-column {
        position: relative;
      }

      .horizontal-section {
        height: auto;
      }

      .stat-grid {
        grid-template-columns: 1fr 1fr;
      }

      .contribution-grid {
        grid-template-columns: repeat(3, minmax(0, 1fr));
      }

      .trophy-scatter-head,
      .trophy-scatter-layout {
        grid-template-columns: 1fr;
      }

      .trophy-scatter-plot,
      .trophy-detail-panel {
        min-height: 500px;
      }

      .career-ledger-row {
        grid-template-columns: 1fr;
      }

      .kit-gallery {
        grid-template-columns: repeat(3, minmax(0, 1fr));
      }

      .league-rank-section {
        min-height: 380vh;
      }

      .league-rank-sticky {
        position: sticky;
        top: 0;
        height: 100svh;
        min-height: 0;
        padding: 0;
        overflow: hidden;
      }

      .league-rank-chart-shell {
        position: absolute;
        left: 50%;
        top: 50%;
      }

      .league-rank-chart-shell {
        top: 4svh;
        width: min(124vw, 42rem);
        margin-bottom: 0;
        transform: translateX(-50%) scale(0.74);
        transform-origin: top center;
      }

      .league-rank-chart-card {
        grid-template-columns: 1fr;
        grid-template-areas:
          "head"
          "insight"
          "plot"
          "axis"
          "source";
        row-gap: 0.8rem;
        padding: 1.05rem;
      }

      .league-rank-chart-top {
        flex-direction: column;
        gap: 0.35rem;
        margin-bottom: 0.7rem;
      }

      .league-rank-chart-top h3 {
        font-size: clamp(2rem, 9vw, 3rem);
        max-width: 18ch;
      }

      .league-rank-plot {
        height: 190px;
      }

      .league-rank-insights {
        position: relative;
        left: auto;
        top: auto;
        width: 100%;
        padding: 0.95rem;
        transform: none;
        opacity: 1;
      }

      .league-rank-season {
        font-size: clamp(2.15rem, 11vw, 3.2rem);
      }

      .league-rank-position {
        margin-top: 0.65rem;
        padding-bottom: 0.75rem;
      }

      .league-rank-position strong {
        font-size: clamp(3.25rem, 18vw, 4.7rem);
      }

      .league-rank-detail {
        margin: 0.75rem 0 0.85rem;
        font-size: 0.9rem;
        line-height: 1.45;
      }

      .league-rank-facts {
        gap: 0.55rem;
        margin-top: 0.8rem;
      }

      .league-rank-fact strong {
        font-size: 1.25rem;
      }

    }

    @media (max-width: 768px) {
      .colors-opening-shell {
        padding: 1.6rem 6vw 2rem;
      }

      .colors-copy {
        width: 100%;
        margin-top: 4.4rem;
        margin-left: 0;
        position: relative;
        z-index: 4;
      }

      .colors-copy h2 {
        font-size: clamp(3.3rem, 18vw, 5.8rem);
      }

      .colors-copy-kicker {
        margin-top: 1.25rem;
        font-size: 0.72rem;
        letter-spacing: 0.14em;
      }

      .colors-copy-lede,
      .colors-copy-detail {
        max-width: 100%;
        font-size: 1rem;
      }

      .colors-palette {
        position: relative;
        right: auto;
        top: auto;
        width: 100%;
        margin-top: 2rem;
      }

      .palette-node {
        grid-template-columns: 92px 1fr 56px;
      }

      .palette-node.is-expanded {
        grid-template-columns: 104px 1fr 56px;
      }

      .palette-node-copy {
        padding: 1rem 1rem 1rem 1.05rem;
      }

      .palette-node-name {
        font-size: 1.45rem;
      }

      .colors-boundary-indicator {
        left: 50%;
        top: 41%;
      }

      .colors-boundary-ring {
        width: 34px;
        height: 34px;
      }

      .colors-stripes {
        height: 22vh;
        opacity: 0.32;
      }

      .hero,
      .closing,
      .panel,
      .contribution-section {
        padding: 10vw 7vw;
      }

      .kit-archive-panel {
        min-height: auto;
        padding: 10vw 7vw;
      }

      .crest-archive-panel {
        min-height: auto;
        padding: 10vw 7vw;
      }

      .kit-preview-sticky {
        position: relative;
        top: 0;
      }

      .crest-preview-sticky {
        position: relative;
        top: 0;
        width: 100%;
      }

      .kit-timeline-rail,
      .kit-timeline-rail.is-floating,
      .kit-timeline-rail.is-bottom {
        position: relative;
        top: auto;
        left: auto;
        bottom: auto;
        width: 100%;
        height: auto;
        overflow: visible;
        mask-image: none;
        -webkit-mask-image: none;
      }

      .crest-timeline-rail,
      .crest-timeline-rail.is-floating,
      .crest-timeline-rail.is-bottom {
        position: relative;
        top: auto;
        left: auto;
        bottom: auto;
        width: 100%;
        height: auto;
        overflow-x: auto;
        overflow-y: visible;
        transform: none;
      }

      .crest-active-guide {
        top: 1rem;
      }

      .crest-era-list {
        padding: 11rem 1rem 1.6rem;
      }

      .crest-era-list::before {
        left: 1rem;
        right: 1rem;
        top: 1.6rem;
      }

      .crest-era-step {
        flex-basis: 168px;
        min-height: 148px;
      }

      .crest-preview-floating {
        left: 50%;
        top: 4.8rem;
        width: min(64vw, 240px);
        transform: translateX(-50%);
      }

      .crest-preview-floating .crest-photo {
        max-height: 180px;
      }

      .archive-shirt {
        width: min(52vw, 220px);
      }

      .horizontal-section {
        height: auto;
      }

      .stat-grid {
        grid-template-columns: 1fr;
      }

      .palette-row {
        grid-template-columns: 1fr;
      }

      .kit-gallery {
        grid-template-columns: 1fr 1fr;
      }

      .contribution-grid {
        grid-template-columns: 1fr 1fr;
      }

      .contribution-card {
        min-height: 30rem;
      }

      .ball-rain {
        height: 21rem;
      }

      .timeline-row {
        grid-template-columns: 1fr;
        gap: 0.3rem;
      }

      .career-total-grid,
      .career-era-item {
        grid-template-columns: 1fr;
      }

      .legacy-ten-panel .panel-main {
        grid-column: auto;
        padding-top: 0;
      }

      .legacy-ten-panel .panel-side {
        grid-column: auto;
      }

      .legacy-ten-stage {
        min-height: 0;
        padding-left: 0;
      }

      .player-spotlight-panel {
        min-height: auto;
        grid-template-columns: 1fr;
        gap: 2rem;
      }

      .player-spotlight-panel .panel-main,
      .player-spotlight-panel .panel-side {
        transform: none;
      }

      .player-spotlight-panel .panel-side {
        position: relative;
        top: auto;
        height: auto;
        justify-items: center;
      }

      .player-spotlight-panel .panel-side.is-fixed,
      .player-spotlight-panel .panel-side.is-bottom {
        position: relative;
        left: auto;
        right: auto;
        bottom: auto;
        width: auto;
        height: auto;
        display: grid;
      }

      .player-portrait-wrap {
        position: relative;
        width: min(88vw, 520px);
        height: auto;
      }

      .player-name-overlay {
        top: 0.8rem;
        left: 0;
        font-size: clamp(2.5rem, 11vw, 4.2rem);
      }

      .player-portrait {
        height: auto;
        max-height: 72vh;
      }

      .timeline-copy {
        padding-left: 0;
        border-left: 0;
      }

      .hero::after {
        width: min(28vw, 120px);
      }

      .hero-crest {
        left: 50%;
        top: 28%;
        width: min(40vw, 260px);
      }

      .hero-motto {
        left: 50%;
        top: 136vh;
        width: min(88vw, 520px);
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <div class="progress">
    <div class="progress-fill" id="progressFill"></div>
  </div>
  <div class="legacy-ten-orb" id="legacyTenOrb" aria-hidden="true">10</div>

  <section class="hero-shell" id="heroSection">
    <div class="hero">
      <div class="hero-crest" id="heroCrest">
        <img class="crest-mark" src="/Users/eddy/Desktop/Barca Logo/2002-Today.png" alt="FC Barcelona crest" />
      </div>
      <div class="hero-copy">
        <div class="eyebrow">Info Visualization</div>
        <h1>FC Barcelona</h1>
        <div class="hero-deck">How style became identity.</div>
        <p>
          This project follows how Barca became recognizable not only by results, but by a way of playing that turned into a cultural image.
        </p>
        <div class="scroll-hint">Scroll to begin</div>
      </div>
    </div>
    <div class="hero-motto" aria-hidden="true">
      <div class="hero-motto-label">FC Barcelona</div>
      <div class="hero-motto-rule"></div>
      <p class="hero-motto-text">Mes que un club.</p>
      <div class="hero-motto-sub">More than a club</div>
    </div>
  </section>

  <section class="horizontal-section" id="horizontalSection">
    <div class="sticky-track">
      <div class="panels" id="panels">
        <article class="panel colors-opening" id="colorsOpening">
          <div class="colors-opening-shell">
            <div class="colors-signature section-signature">
              <div class="panel-index">01 / Colors</div>
              <div class="headline-rule"></div>
            </div>

            <div class="colors-copy">
              <h2>Blaugrana<br />as identity.</h2>
              <div class="colors-copy-kicker">
                <span class="colors-copy-kicker-line"></span>
                <span>Not a colour pair. A club identity.</span>
              </div>
              <p class="colors-copy-lede">
                Blaugrana starts as opposition: heat against depth, pressure against control, two forces learning how to wear the same shirt.
              </p>
              <p class="colors-copy-detail">
                At the point of collision, colour stops being palette and becomes identity.
              </p>
            </div>

            <div class="colors-palette" id="colorsPalette">
              <button class="palette-node is-expanded" type="button" data-palette-node data-color-key="red" aria-expanded="true">
                <span class="palette-node-swatch is-red" aria-hidden="true"></span>
                <span class="palette-node-copy">
                  <span class="palette-node-role">Primary colour</span>
                  <span class="palette-node-name">Garnet Red</span>
                  <span class="palette-node-note">Heat, urgency, and the emotional charge that turns the shirt into a signal.</span>
                  <span class="palette-node-meta">#A50044</span>
                </span>
                <span class="palette-node-toggle" aria-hidden="true"></span>
              </button>

              <button class="palette-node" type="button" data-palette-node data-color-key="blue" aria-expanded="false">
                <span class="palette-node-swatch is-blue" aria-hidden="true"></span>
                <span class="palette-node-copy">
                  <span class="palette-node-role">Primary colour</span>
                  <span class="palette-node-name">Royal Blue</span>
                  <span class="palette-node-note">Structure, depth, and the cool composure that keeps the whole identity legible.</span>
                  <span class="palette-node-meta">#004D98</span>
                </span>
                <span class="palette-node-toggle" aria-hidden="true"></span>
              </button>

              <button class="palette-node" type="button" data-palette-node data-color-key="gold" aria-expanded="false">
                <span class="palette-node-swatch is-gold" aria-hidden="true"></span>
                <span class="palette-node-copy">
                  <span class="palette-node-role">Accent colour</span>
                  <span class="palette-node-name">Catalan Gold</span>
                  <span class="palette-node-note">A restrained highlight carrying heritage, prestige, and archive-era punctuation.</span>
                  <span class="palette-node-meta">#F2C14E</span>
                </span>
                <span class="palette-node-toggle" aria-hidden="true"></span>
              </button>
            </div>

          </div>
        </article>

        <article class="panel kit-archive-panel section-signature" id="kitArchivePanel">
          <div class="kit-archive-layout">
            <div class="kit-preview-column">
              <div class="kit-preview-sticky">
                <div class="panel-index">02 / Home Kit Archive</div>
                <div class="headline-rule"></div>
                <h2>Barca<br>Home&nbsp;Jersey</h2>
                  <div class="kit-preview-card">
                  <div class="kit-preview-header">
                    <div class="kit-preview-season" id="kitPreviewSeason">1990/91</div>
                    <div class="kit-preview-tag" id="kitPreviewTag">Archive View</div>
                  </div>
                  <div class="kit-stage">
                    <img class="archive-shirt-photo" id="kitPreviewPhoto" alt="Barcelona home shirt preview" />
                    <div class="archive-shirt" id="kitPreviewShirt"></div>
                  </div>
                  <p class="kit-preview-note" id="kitPreviewNote">
                    Half-and-half blaugrana blocks mark the opening point of the archive.
                  </p>
                  <div class="kit-preview-meta" id="kitPreviewMeta">Home shirt / visual study</div>
                </div>
              </div>
            </div>

            <div class="kit-timeline-column">
              <div class="kit-timeline-rail" id="kitTimelineRail">
                <div class="kit-season-list" id="kitSeasonList"></div>
              </div>
            </div>
          </div>
        </article>

        <article class="panel crest-archive-panel section-signature" id="crestPanel">
          <div class="crest-archive-layout">
            <div class="crest-preview-column">
              <div class="crest-preview-sticky">
                <div class="panel-index">03 / Crest Archive</div>
                <div class="headline-rule"></div>
                <h2>Barca Crest Archive</h2>
                <div class="crest-preview-header">
                  <div class="crest-preview-era" id="crestPreviewEra">1899-1910</div>
                  <div class="crest-preview-tag" id="crestPreviewTag">Founding emblem</div>
                </div>
                <p class="crest-preview-note" id="crestPreviewNote">
                  The first emblem is still closer to a civic seal than a football badge, binding club identity to the city.
                </p>
                <div class="crest-preview-meta" id="crestPreviewMeta">Crest archive / visual timeline</div>
              </div>
            </div>

            <div class="crest-timeline-column">
              <div class="crest-timeline-rail" id="crestTimelineRail">
                <div class="crest-active-guide" aria-hidden="true">
                  <div class="crest-active-guide-triangle" id="crestActiveGuideTriangle"></div>
                </div>
                <div class="crest-preview-floating">
                  <div class="crest-stage">
                    <img class="crest-photo" id="crestPreviewPhoto" alt="Barcelona crest archive preview" />
                  </div>
                </div>
                <div class="crest-era-list" id="crestEraList"></div>
              </div>
            </div>
          </div>
        </article>

        <article class="panel legacy-ten-panel section-signature" id="legacyTenPanel">
          <div class="panel-main">
            <div class="panel-index">04 / Number 10</div>
            <div class="headline-rule"></div>
            <h2>The tradition of the 10.</h2>
            <p class="lede">
              At Barcelona, the number 10 is more than a shirt number. It is a symbol of imagination, responsibility, and the pressure of carrying the club's creative identity onto the pitch. Across different eras, the player who wears it is often expected not only to perform, but to define the rhythm, spirit, and vision of the team.
            </p>
            <p class="detail">
              The meaning of the 10 at Barca was shaped over time. It came to represent elegance under pressure, technical brilliance, and the ability to turn football into expression. More than goals or statistics, the number carries memory passed from one generation to the next, with each player adding a new layer to its mythology.
            </p>
          </div>

          <div class="panel-side">
            <div class="legacy-ten-stage">
              <div class="legacy-ten-kicker">A legacy in motion</div>
              <p class="legacy-ten-caption">
                As the club changed, the meaning of the 10 changed with it. Yet its core remained the same: invention, leadership, and the promise of something unforgettable. At Barcelona, the number 10 is not simply inherited. It is reinterpreted.
              </p>
            </div>
          </div>
        </article>

        <article class="panel player-spotlight-panel" id="maradonaPanel">
          <div class="panel-main">
            <div class="panel-index">04A / Maradona</div>
            <div class="headline-rule"></div>
            <div class="player-kicker">First focus</div>
            <h2>Maradona as the first modern 10 icon.</h2>
            <div class="maradona-accent-bar" aria-hidden="true"><span></span><span></span></div>
            <p class="lede">
              Before the mythology of later decades fully settled, Diego Maradona gave Barcelona's number 10 its first modern superstar silhouette. His spell was brief, turbulent, and incomplete, but it established the shirt as a space where genius, pressure, and theatre could all live at once.
            </p>
            <p class="detail">
              The data on the left does not describe a fully realized Barcelona era so much as an ignition point. The scale is smaller than later legends, yet the visual argument begins here: the number 10 becomes a role that concentrates invention, celebrity, and the expectation of unforgettable moments.
            </p>
            <div class="player-stats-board">
              <div class="player-group-title">Season-by-season output</div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">1982/83</div>
                  <div class="season-summary">First season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">35 / 40</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 87.5%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">23</div>
                  </div>
                  <div class="player-stat-icons" aria-label="23 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">18</div>
                  </div>
                  <div class="player-stat-icons" aria-label="18 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa de la Liga</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">1983/84</div>
                  <div class="season-summary">Second season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">23 / 40</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 57.5%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">15</div>
                  </div>
                  <div class="player-stat-icons" aria-label="15 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">5</div>
                  </div>
                  <div class="player-stat-icons" aria-label="5 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="panel-side">
            <div class="player-portrait-wrap" aria-label="Maradona portrait">
              <div class="player-flag-layer" aria-hidden="true">
                <img
                  src="/Users/eddy/Desktop/Barca 10/Argentina Flag.png"
                  alt=""
                />
              </div>
              <div class="player-name-overlay" aria-hidden="true">
                <span class="outline">Diego</span>
                <span class="display-name">Maradona</span>
                <div class="player-name-caption">
                  <span>FC Barcelona</span>
                  <span>1982-1984</span>
                </div>
              </div>
              <img
                class="player-portrait"
                src="/Users/eddy/Desktop/Barca 10/Maradona.png"
                alt="Diego Maradona in a Barcelona shirt"
              />
            </div>
          </div>
        </article>

        <article class="panel player-spotlight-panel" id="romarioPanel">
          <div class="panel-main">
            <div class="panel-index">04B / Romario</div>
            <div class="headline-rule"></div>
            <div class="player-kicker">Next focus</div>
            <h2>Romario as the ruthless finisher of the Dream Team.</h2>
            <div class="maradona-accent-bar" aria-hidden="true"><span></span><span></span></div>
            <p class="lede">
              If Maradona gave the Barcelona number 10 its first volatile superstar silhouette, Romario gave it something colder and more surgical: a striker's economy inside a playmaker's shirt. His presence condensed Cruyff's attacking system into quick touches, short accelerations, and devastating finishing.
            </p>
            <p class="detail">
              Romario's Barcelona spell was shorter than its legend, but the peak was undeniable. In one title-winning season he turned the number 10 into an instrument of efficiency, where imagination was measured not by spectacle alone, but by how brutally fast a move could end in a goal.
            </p>
            <div class="player-stats-board">
              <div class="player-group-title">Season-by-season output</div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">1993/94</div>
                  <div class="season-summary">Dream Team peak</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">47 / 50</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 94%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">32</div>
                  </div>
                  <div class="player-stat-icons" aria-label="32 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">14</div>
                  </div>
                  <div class="player-stat-icons" aria-label="14 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">1994/95</div>
                  <div class="season-summary">Second season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">18 / 50</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 36%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">7</div>
                  </div>
                  <div class="player-stat-icons" aria-label="7 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">3</div>
                  </div>
                  <div class="player-stat-icons" aria-label="3 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="panel-side">
            <div class="player-portrait-wrap" aria-label="Romario portrait">
              <div class="player-flag-layer" aria-hidden="true">
                <img
                  src="/Users/eddy/Desktop/Barca 10/Brazil Flag.png"
                  alt=""
                />
              </div>
              <div class="player-name-overlay" aria-hidden="true">
                <span class="outline">Romario</span>
                <span class="display-name">Romario</span>
                <div class="player-name-caption">
                  <span>FC Barcelona</span>
                  <span>1993-1995</span>
                </div>
              </div>
              <img
                class="player-portrait"
                src="/Users/eddy/Desktop/Barca 10/Romario.png"
                alt="Romario in a Barcelona shirt"
              />
            </div>
          </div>
        </article>

        <article class="panel player-spotlight-panel" id="rivaldoPanel">
          <div class="panel-main">
            <div class="panel-index">04C / Rivaldo</div>
            <div class="headline-rule"></div>
            <div class="player-kicker">Next focus</div>
            <h2>Rivaldo as the spectacular force of the late 1990s.</h2>
            <div class="maradona-accent-bar" aria-hidden="true"><span></span><span></span></div>
            <p class="lede">
              If Romario made the Barcelona number 10 feel ruthless, Rivaldo made it feel volcanic again. He restored drama to the shirt: left-footed range, sudden overhead improvisation, and the sense that a match could be bent by one act of invention from distance.
            </p>
            <p class="detail">
              Rivaldo's years at Barca stretched across a more complex era, but they gave the number 10 a new kind of authority. He carried goals, playmaking, and star power at once, turning the role into a stage where elegance and violence could exist in the same movement.
            </p>
            <div class="player-stats-board">
              <div class="player-group-title">Season-by-season output</div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">1997/98</div>
                  <div class="season-summary">Arrival season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">50 / 55</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 90.9%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">24</div>
                  </div>
                  <div class="player-stat-icons" aria-label="24 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">13</div>
                  </div>
                  <div class="player-stat-icons" aria-label="13 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>UEFA Super Cup</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">1998/99</div>
                  <div class="season-summary">Ballon d'Or year</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">47 / 55</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 85.5%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">29</div>
                  </div>
                  <div class="player-stat-icons" aria-label="29 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">17</div>
                  </div>
                  <div class="player-stat-icons" aria-label="17 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2000/01</div>
                  <div class="season-summary">Peak output</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">53 / 55</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 96.4%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">36</div>
                  </div>
                  <div class="player-stat-icons" aria-label="36 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">12</div>
                  </div>
                  <div class="player-stat-icons" aria-label="12 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">1999/00</div>
                  <div class="season-summary">Carry season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">48 / 55</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 87.3%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">23</div>
                  </div>
                  <div class="player-stat-icons" aria-label="23 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">11</div>
                  </div>
                  <div class="player-stat-icons" aria-label="11 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2001/02</div>
                  <div class="season-summary">Final season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">49 / 55</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 89.1%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">23</div>
                  </div>
                  <div class="player-stat-icons" aria-label="23 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">12</div>
                  </div>
                  <div class="player-stat-icons" aria-label="12 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="panel-side">
            <div class="player-portrait-wrap" aria-label="Rivaldo portrait">
              <div class="player-flag-layer" aria-hidden="true">
                <img
                  src="/Users/eddy/Desktop/Barca 10/Brazil Flag.png"
                  alt=""
                />
              </div>
              <div class="player-name-overlay" aria-hidden="true">
                <span class="outline">Rivaldo</span>
                <span class="display-name">Rivaldo</span>
                <div class="player-name-caption">
                  <span>FC Barcelona</span>
                  <span>1997-2002</span>
                </div>
              </div>
              <img
                class="player-portrait"
                src="/Users/eddy/Desktop/Barca 10/Rivaldo.png"
                alt="Rivaldo in a Barcelona shirt"
              />
            </div>
          </div>
        </article>

        <article class="panel player-spotlight-panel" id="ronaldinhoPanel">
          <div class="panel-main">
            <div class="panel-index">04D / Ronaldinho</div>
            <div class="headline-rule"></div>
            <div class="player-kicker">Next focus</div>
            <h2>Ronaldinho as the joyful rebirth of Barcelona's 10.</h2>
            <div class="maradona-accent-bar" aria-hidden="true"><span></span><span></span></div>
            <p class="lede">
              If Rivaldo made the shirt feel explosive, Ronaldinho made it feel liberating. He turned the Barcelona number 10 into a public celebration again: elastic dribbling, impossible passing angles, and the kind of smile that made dominance look playful.
            </p>
            <p class="detail">
              Ronaldinho did more than carry the role. He reset the mood of the club around it. In his hands, the 10 became a symbol not only of genius, but of joy, spectacle, and the feeling that Barca could once again enchant Europe as well as defeat it.
            </p>
            <div class="player-stats-board">
              <div class="player-group-title">Season-by-season output</div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2003/04</div>
                  <div class="season-summary">Revival begins</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">45 / 50</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 90%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">22</div>
                  </div>
                  <div class="player-stat-icons" aria-label="22 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">12</div>
                  </div>
                  <div class="player-stat-icons" aria-label="12 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2004/05</div>
                  <div class="season-summary">League return</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">42 / 50</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 84%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">17</div>
                  </div>
                  <div class="player-stat-icons" aria-label="17 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">17</div>
                  </div>
                  <div class="player-stat-icons" aria-label="17 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2005/06</div>
                  <div class="season-summary">European peak</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">45 / 50</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 90%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">26</div>
                  </div>
                  <div class="player-stat-icons" aria-label="26 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">24</div>
                  </div>
                  <div class="player-stat-icons" aria-label="24 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Champions League</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2006/07</div>
                  <div class="season-summary">Carry season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">47 / 50</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 94%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">24</div>
                  </div>
                  <div class="player-stat-icons" aria-label="24 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">17</div>
                  </div>
                  <div class="player-stat-icons" aria-label="17 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2007/08</div>
                  <div class="season-summary">Final season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">26 / 50</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 52%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">10</div>
                  </div>
                  <div class="player-stat-icons" aria-label="10 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">13</div>
                  </div>
                  <div class="player-stat-icons" aria-label="13 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="panel-side">
            <div class="player-portrait-wrap" aria-label="Ronaldinho portrait">
              <div class="player-flag-layer" aria-hidden="true">
                <img
                  src="/Users/eddy/Desktop/Barca 10/Brazil Flag.png"
                  alt=""
                />
              </div>
              <div class="player-name-overlay" aria-hidden="true">
                <span class="outline">Ronaldinho</span>
                <span class="display-name">Ronaldinho</span>
                <div class="player-name-caption">
                  <span>FC Barcelona</span>
                  <span>2003-2008</span>
                </div>
              </div>
              <img
                class="player-portrait"
                src="/Users/eddy/Desktop/Barca 10/Ronaldinho.png"
                alt="Ronaldinho in a Barcelona shirt"
              />
            </div>
          </div>
        </article>

        <article class="panel player-spotlight-panel" id="messiPanel">
          <div class="panel-main">
            <div class="panel-index">04E / Messi</div>
            <div class="headline-rule"></div>
            <div class="player-kicker">Next focus</div>
            <h2>Messi as the complete realization of Barcelona's 10.</h2>
            <div class="maradona-accent-bar" aria-hidden="true"><span></span><span></span></div>
            <p class="lede">
              If Ronaldinho reopened the magic of the number 10, Messi turned it into Barcelona's final operating system. The shirt no longer represented just flair or possibility. In his hands it became a total framework: creation, finishing, tempo control, gravity, and relentless output inside one body.
            </p>
            <p class="detail">
              Messi did not simply inherit the Barcelona 10. He absorbed every previous version of it and pushed them into a complete form. The dribbler, the playmaker, the scorer, the closer, the organizer of space, and the emotional centre of the club all converged here, over 778 official matches and the most productive spell any Barcelona player has ever authored.
            </p>
            <div class="player-stats-board">
              <div class="player-group-title">Season-by-season output</div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2004/05</div>
                  <div class="season-summary">Debut year</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">9 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 15.0%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">1</div>
                  </div>
                  <div class="player-stat-icons" aria-label="1 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">0</div>
                  </div>
                  <div class="player-stat-icons" aria-label="0 assists">
                    
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2005/06</div>
                  <div class="season-summary">First double</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">25 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 41.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">8</div>
                  </div>
                  <div class="player-stat-icons" aria-label="8 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">5</div>
                  </div>
                  <div class="player-stat-icons" aria-label="5 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Champions League</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2006/07</div>
                  <div class="season-summary">Explosion begins</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">36 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 60.0%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">17</div>
                  </div>
                  <div class="player-stat-icons" aria-label="17 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">3</div>
                  </div>
                  <div class="player-stat-icons" aria-label="3 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2007/08</div>
                  <div class="season-summary">Central creator</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">40 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 66.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">16</div>
                  </div>
                  <div class="player-stat-icons" aria-label="16 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">16</div>
                  </div>
                  <div class="player-stat-icons" aria-label="16 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2008/09</div>
                  <div class="season-summary">Treble breakthrough</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">51 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 85.0%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">38</div>
                  </div>
                  <div class="player-stat-icons" aria-label="38 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">19</div>
                  </div>
                  <div class="player-stat-icons" aria-label="19 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Champions League</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2009/10</div>
                  <div class="season-summary">Golden Shoe rise</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">53 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 88.3%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">47</div>
                  </div>
                  <div class="player-stat-icons" aria-label="47 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">12</div>
                  </div>
                  <div class="player-stat-icons" aria-label="12 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>UEFA Super Cup</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Club World Cup</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2010/11</div>
                  <div class="season-summary">European control</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">55 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 91.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">53</div>
                  </div>
                  <div class="player-stat-icons" aria-label="53 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">27</div>
                  </div>
                  <div class="player-stat-icons" aria-label="27 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Champions League</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2011/12</div>
                  <div class="season-summary">Statistical peak</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">60 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 100.0%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">73</div>
                  </div>
                  <div class="player-stat-icons" aria-label="73 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">32</div>
                  </div>
                  <div class="player-stat-icons" aria-label="32 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>UEFA Super Cup</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Club World Cup</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2012/13</div>
                  <div class="season-summary">League record pace</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">50 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 83.3%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">60</div>
                  </div>
                  <div class="player-stat-icons" aria-label="60 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">17</div>
                  </div>
                  <div class="player-stat-icons" aria-label="17 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2013/14</div>
                  <div class="season-summary">Injury-hit transition</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">46 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 76.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">41</div>
                  </div>
                  <div class="player-stat-icons" aria-label="41 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">14</div>
                  </div>
                  <div class="player-stat-icons" aria-label="14 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2014/15</div>
                  <div class="season-summary">Second treble</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">57 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 95.0%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">58</div>
                  </div>
                  <div class="player-stat-icons" aria-label="58 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">31</div>
                  </div>
                  <div class="player-stat-icons" aria-label="31 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Champions League</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2015/16</div>
                  <div class="season-summary">MSN dominance</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">49 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 81.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">41</div>
                  </div>
                  <div class="player-stat-icons" aria-label="41 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">24</div>
                  </div>
                  <div class="player-stat-icons" aria-label="24 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>UEFA Super Cup</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Club World Cup</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2016/17</div>
                  <div class="season-summary">Final Copa under Luis Enrique</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">52 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 86.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">54</div>
                  </div>
                  <div class="player-stat-icons" aria-label="54 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">20</div>
                  </div>
                  <div class="player-stat-icons" aria-label="20 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2017/18</div>
                  <div class="season-summary">Double as focal point</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">54 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 90.0%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">45</div>
                  </div>
                  <div class="player-stat-icons" aria-label="45 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">20</div>
                  </div>
                  <div class="player-stat-icons" aria-label="20 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2018/19</div>
                  <div class="season-summary">Captain and Pichichi</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">50 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 83.3%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">51</div>
                  </div>
                  <div class="player-stat-icons" aria-label="51 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">22</div>
                  </div>
                  <div class="player-stat-icons" aria-label="22 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2019/20</div>
                  <div class="season-summary">Carry season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">44 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 73.3%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">31</div>
                  </div>
                  <div class="player-stat-icons" aria-label="31 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">27</div>
                  </div>
                  <div class="player-stat-icons" aria-label="27 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2020/21</div>
                  <div class="season-summary">Final Barca season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">47 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 78.3%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">38</div>
                  </div>
                  <div class="player-stat-icons" aria-label="38 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">14</div>
                  </div>
                  <div class="player-stat-icons" aria-label="14 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="panel-side">
            <div class="player-portrait-wrap" aria-label="Messi portrait">
              <div class="player-flag-layer" aria-hidden="true">
                <img
                  src="/Users/eddy/Desktop/Barca 10/Argentina Flag.png"
                  alt=""
                />
              </div>
              <div class="player-name-overlay" aria-hidden="true">
                <span class="outline">Lionel</span>
                <span class="display-name">Messi</span>
                <div class="player-name-caption">
                  <span>FC Barcelona</span>
                  <span>2004-2021</span>
                </div>
              </div>
              <img
                class="player-portrait"
                src="/Users/eddy/Desktop/Barca 10/Messi.png"
                alt="Lionel Messi in a Barcelona shirt"
              />
            </div>
          </div>
        </article>


        <article class="panel player-spotlight-panel" id="yamalPanel">
          <div class="panel-main">
            <div class="panel-index">04F / Yamal</div>
            <div class="headline-rule"></div>
            <div class="player-kicker">Next focus</div>
            <h2>Yamal as the next mutation of Barcelona's 10.</h2>
            <div class="maradona-accent-bar" aria-hidden="true"><span></span><span></span></div>
            <p class="lede">
              If Messi completed the mythology, Lamine Yamal reopens the future. His version of Barcelona's 10 is still forming, but the early outline is already unmistakable: acceleration, left-footed invention, fearless one-v-one play, and the sense that the shirt has found another young centre of gravity.
            </p>
            <p class="detail">
              Yamal's story is not complete yet, which is exactly what gives this section its charge. From a one-match debut in 2022/23 to a full frontline role, his Barcelona career is already moving at historic speed. The current 2025/26 figures below are shown through April 22, 2026.
            </p>
            <div class="player-stats-board">
              <div class="player-group-title">Season-by-season output</div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2022/23</div>
                  <div class="season-summary">Debut cameo</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">1 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 1.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">0</div>
                  </div>
                  <div class="player-stat-icons" aria-label="0 goals">
                    
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">0</div>
                  </div>
                  <div class="player-stat-icons" aria-label="0 assists">
                    
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2023/24</div>
                  <div class="season-summary">Breakthrough season</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">50 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 83.3%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">7</div>
                  </div>
                  <div class="player-stat-icons" aria-label="7 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">9</div>
                  </div>
                  <div class="player-stat-icons" aria-label="9 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2024/25</div>
                  <div class="season-summary">Global breakout</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">55 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 91.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">18</div>
                  </div>
                  <div class="player-stat-icons" aria-label="18 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">25</div>
                  </div>
                  <div class="player-stat-icons" aria-label="25 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>La Liga</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Copa del Rey</span>
                  </div>
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>

              <div class="season-card">
                <div class="season-header">
                  <div class="season-year">2025/26</div>
                  <div class="season-summary">Current campaign</div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Appearances</div>
                    <div class="player-stat-value">40 / 60</div>
                  </div>
                  <div class="player-stat-bar is-apps" style="--fill: 66.7%;">
                    <span></span>
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Goals</div>
                    <div class="player-stat-value">21</div>
                  </div>
                  <div class="player-stat-icons" aria-label="21 goals">
                    <img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" /><img class="stat-icon is-ball" src="/Users/eddy/Desktop/Barca Icon/Goal.png" alt="" />
                  </div>
                </div>

                <div class="season-stat-row">
                  <div class="player-stat-meta">
                    <div class="player-stat-label">Assists</div>
                    <div class="player-stat-value">16</div>
                  </div>
                  <div class="player-stat-icons" aria-label="16 assists">
                    <img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" /><img class="stat-icon is-assist" src="/Users/eddy/Desktop/Barca Icon/Assist.png" alt="" />
                  </div>
                </div>

                <div class="season-trophies">
                  <div class="trophy-badge">
                    <span class="trophy-icon"></span>
                    <span class="trophy-stem"></span>
                    <span>Supercopa de Espana</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="panel-side">
            <div class="player-portrait-wrap" aria-label="Yamal portrait">
              <div class="player-flag-layer" aria-hidden="true">
                <img
                  src="/Users/eddy/Desktop/Barca 10/Spain Flag.png"
                  alt=""
                />
              </div>
              <div class="player-name-overlay" aria-hidden="true">
                <span class="outline">Lamine</span>
                <span class="display-name">Yamal</span>
                <div class="player-name-caption">
                  <span>FC Barcelona</span>
                  <span>2022-Present</span>
                </div>
              </div>
              <img
                class="player-portrait"
                src="/Users/eddy/Desktop/Barca 10/Yamal.png"
                alt="Lamine Yamal in a Barcelona shirt"
              />
            </div>
          </div>
        </article>
  </section>

  <section class="contribution-section" id="contributionSection">
    <div class="contribution-head">
      <div>
        <div class="contribution-signature">
          <div class="panel-index">05 / Data View</div>
          <div class="headline-rule"></div>
        </div>
        <h3>Six No.10 stories, one direct-output comparison.</h3>
      </div>
      <div class="contribution-copy">
        <p>This panel compares how much direct attacking output each of these six Barcelona number 10 figures produced for the club. The number shown is goals plus assists; the rain of footballs underneath is scaled so that heavier production literally falls more densely.</p>
        <div class="contribution-scale">1 Ball = 20 Goal Contributions</div>
      </div>
    </div>
    <div class="contribution-grid" id="contributionGrid"></div>

    <div class="trophy-scatter-block" id="trophyScatterBlock">
      <div class="trophy-scatter-head">
        <div>
          <div class="trophy-scatter-kicker">Appearances × trophies</div>
          <h4>Silverware against time in the shirt.</h4>
        </div>
        <p class="trophy-scatter-copy">
          A second view of the same six number 10 stories: the horizontal axis measures Barcelona appearances, while the vertical axis tracks trophies won during the spell shown in the player panels.
        </p>
      </div>

      <div class="trophy-scatter-layout">
        <div class="trophy-scatter-plot" id="trophyScatterPlot" aria-label="Scatter plot comparing appearances and trophies for six Barcelona number 10 players">
          <div class="trophy-plot-area">
            <div class="trophy-gridline is-y" style="--offset: 0%;"><em>0</em></div>
            <div class="trophy-gridline is-y" style="--offset: 25%;"><em>10</em></div>
            <div class="trophy-gridline is-y" style="--offset: 50%;"><em>20</em></div>
            <div class="trophy-gridline is-y" style="--offset: 75%;"><em>30</em></div>
            <div class="trophy-gridline is-y" style="--offset: 100%;"><em>40</em></div>
            <div class="trophy-gridline is-x" style="--offset: 0%;"><em>0</em></div>
            <div class="trophy-gridline is-x" style="--offset: 25%;"><em>200</em></div>
            <div class="trophy-gridline is-x" style="--offset: 50%;"><em>400</em></div>
            <div class="trophy-gridline is-x" style="--offset: 75%;"><em>600</em></div>
            <div class="trophy-gridline is-x" style="--offset: 100%;"><em>800</em></div>
            <div class="trophy-focus-line is-x" aria-hidden="true"></div>
            <div class="trophy-focus-line is-y" aria-hidden="true"></div>
            <div class="trophy-scatter-points" id="trophyScatterPoints"></div>
          </div>
          <div class="trophy-axis-label is-y">Trophies</div>
          <div class="trophy-axis-label is-x">Appearances</div>
        </div>

        <aside class="trophy-detail-panel" id="trophyDetailPanel" aria-live="polite">
          <div class="trophy-detail-kicker">Selected no.10</div>
          <div class="trophy-detail-name" id="trophyDetailName">Messi</div>
          <div class="trophy-detail-era" id="trophyDetailEra">2004-2021</div>
          <div class="trophy-detail-stats">
            <div class="trophy-detail-stat">
              <strong id="trophyDetailApps">778</strong>
              <span>Appearances</span>
            </div>
            <div class="trophy-detail-stat">
              <strong id="trophyDetailTrophies">35</strong>
              <span>Trophies</span>
            </div>
            <div class="trophy-detail-stat">
              <strong id="trophyDetailRate">22.2</strong>
              <span>Apps per trophy</span>
            </div>
            <div class="trophy-detail-stat">
              <strong id="trophyDetailShare">88%</strong>
              <span>Of chart ceiling</span>
            </div>
          </div>
          <p class="trophy-detail-copy" id="trophyDetailCopy">
            Messi stretches the scale: the only point combining extreme longevity with trophy dominance.
          </p>
          <div class="trophy-detail-note" id="trophyDetailNote">Peak outlier: high appearances, high trophies.</div>
          <div class="trophy-player-rail" id="trophyPlayerRail"></div>
        </aside>
      </div>
    </div>
  </section>

  <section class="league-rank-section" id="leagueRankSection" aria-labelledby="leagueRankTitle">
    <div class="league-rank-sticky">
      <div class="league-rank-backdrop" aria-hidden="true"></div>
      <div class="league-rank-chart-shell">
        <div class="league-rank-signature">
          <div class="panel-index">06 / League Rank</div>
          <div class="headline-rule"></div>
        </div>
        <div class="league-rank-chart-card">
          <div class="league-rank-chart-top">
            <div>
              <p class="league-rank-kicker">La Liga final position</p>
              <h3 id="leagueRankTitle">Barça league rank, 1980-2025.</h3>
            </div>
          </div>

          <aside class="league-rank-insights" aria-live="polite">
            <div class="league-rank-data-label">Selected season</div>
            <div class="league-rank-season" id="leagueRankSeason">1980-81</div>
            <div class="league-rank-position">
              <strong id="leagueRankPosition">5th</strong>
              <span id="leagueRankStatus">Outside top four</span>
            </div>
            <p class="league-rank-detail" id="leagueRankDetail">
              The timeline begins with a volatile early-1980s finish before the Cruyff era pulls the bars back toward the top line.
            </p>
            <div class="league-rank-era" id="leagueRankEra">Pre-Dream Team reset</div>
            <div class="league-rank-facts">
              <div class="league-rank-fact">
                <strong id="leagueRankTitles">19</strong>
                <span>Titles since 1980</span>
              </div>
              <div class="league-rank-fact">
                <strong id="leagueRankTopTwo">33</strong>
                <span>Top-two finishes</span>
              </div>
              <div class="league-rank-fact">
                <strong id="leagueRankAverage">2.1</strong>
                <span>Average rank</span>
              </div>
            </div>
          </aside>

          <div class="league-rank-plot" aria-label="FC Barcelona La Liga final ranking from 1980-81 to 2024-25">
            <div class="league-rank-plot-area">
              <div class="league-rank-gridline" style="--line-top: 0%;"><span>1st</span></div>
              <div class="league-rank-gridline" style="--line-top: 20%;"><span>2nd</span></div>
              <div class="league-rank-gridline" style="--line-top: 40%;"><span>3rd</span></div>
              <div class="league-rank-gridline" style="--line-top: 60%;"><span>4th</span></div>
              <div class="league-rank-gridline" style="--line-top: 80%;"><span>5th</span></div>
              <div class="league-rank-gridline" style="--line-top: 100%;"><span>6th</span></div>
              <div class="league-rank-bars" id="leagueRankChart"></div>
            </div>
          </div>
          <div class="league-rank-axis-row" aria-hidden="true">
            <span>1980</span>
            <span>1990</span>
            <span>2000</span>
            <span>2010</span>
            <span>2025</span>
          </div>
          <div class="league-rank-source">Completed seasons through 2024-25. Source: List of FC Barcelona seasons.</div>
        </div>
      </div>
    </div>
  </section>

  <section class="closing">
    <div>
      <div class="closing-signature">
        <div class="panel-index">07 / Next Step</div>
        <div class="headline-rule"></div>
      </div>
      <h3>Turn this demo into a full research-driven story page.</h3>
    </div>
    <div class="closing-card">
      <p>
        The next iteration can deepen the sourcing layer even further, add quotations from club archives or biographies,
        and expand the statistical storytelling into more player pages. Structurally, the storytelling frame is already here.
      </p>
    </div>
  </section>

  <script>
    const heroSection = document.getElementById("heroSection");
    const heroCrest = document.getElementById("heroCrest");
    const heroMotto = document.querySelector(".hero-motto");
    const progressFill = document.getElementById("progressFill");
    const crestPanel = document.getElementById("crestPanel");
    const legacyTenPanel = document.getElementById("legacyTenPanel");
    const legacyTenOrb = document.getElementById("legacyTenOrb");
    const maradonaPanel = document.getElementById("maradonaPanel");
    const romarioPanel = document.getElementById("romarioPanel");
    const rivaldoPanel = document.getElementById("rivaldoPanel");
    const ronaldinhoPanel = document.getElementById("ronaldinhoPanel");
    const messiPanel = document.getElementById("messiPanel");
    const yamalPanel = document.getElementById("yamalPanel");
    const colorsOpening = document.getElementById("colorsOpening");
    const kitArchivePanel = document.getElementById("kitArchivePanel");
    const kitPreviewColumn = document.querySelector(".kit-preview-column");
    const kitPreviewSticky = document.querySelector(".kit-preview-sticky");
    const kitTimelineRail = document.getElementById("kitTimelineRail");
    const kitSeasonList = document.getElementById("kitSeasonList");
    const kitPreviewSeason = document.getElementById("kitPreviewSeason");
    const kitPreviewTag = document.getElementById("kitPreviewTag");
    const kitPreviewPhoto = document.getElementById("kitPreviewPhoto");
    const kitPreviewShirt = document.getElementById("kitPreviewShirt");
    const kitPreviewNote = document.getElementById("kitPreviewNote");
    const kitPreviewMeta = document.getElementById("kitPreviewMeta");
    const crestPreviewColumn = document.querySelector(".crest-preview-column");
    const crestPreviewSticky = document.querySelector(".crest-preview-sticky");
    const crestTimelineRail = document.getElementById("crestTimelineRail");
    const crestActiveGuideTriangle = document.getElementById("crestActiveGuideTriangle");
    const crestEraList = document.getElementById("crestEraList");
    const crestPreviewEra = document.getElementById("crestPreviewEra");
    const crestPreviewTag = document.getElementById("crestPreviewTag");
    const crestPreviewPhoto = document.getElementById("crestPreviewPhoto");
    const crestPreviewNote = document.getElementById("crestPreviewNote");
    const crestPreviewMeta = document.getElementById("crestPreviewMeta");
    const contributionSection = document.getElementById("contributionSection");
    const contributionGrid = document.getElementById("contributionGrid");
    const trophyScatterBlock = document.getElementById("trophyScatterBlock");
    const trophyScatterPlot = document.getElementById("trophyScatterPlot");
    const trophyScatterPoints = document.getElementById("trophyScatterPoints");
    const trophyDetailPanel = document.getElementById("trophyDetailPanel");
    const trophyDetailName = document.getElementById("trophyDetailName");
    const trophyDetailEra = document.getElementById("trophyDetailEra");
    const trophyDetailApps = document.getElementById("trophyDetailApps");
    const trophyDetailTrophies = document.getElementById("trophyDetailTrophies");
    const trophyDetailRate = document.getElementById("trophyDetailRate");
    const trophyDetailShare = document.getElementById("trophyDetailShare");
    const trophyDetailCopy = document.getElementById("trophyDetailCopy");
    const trophyDetailNote = document.getElementById("trophyDetailNote");
    const trophyPlayerRail = document.getElementById("trophyPlayerRail");
    const leagueRankSection = document.getElementById("leagueRankSection");
    const leagueRankSticky = leagueRankSection?.querySelector(".league-rank-sticky");
    const leagueRankChart = document.getElementById("leagueRankChart");
    const leagueRankSeason = document.getElementById("leagueRankSeason");
    const leagueRankPosition = document.getElementById("leagueRankPosition");
    const leagueRankStatus = document.getElementById("leagueRankStatus");
    const leagueRankDetail = document.getElementById("leagueRankDetail");
    const leagueRankEra = document.getElementById("leagueRankEra");
    const leagueRankTitles = document.getElementById("leagueRankTitles");
    const leagueRankTopTwo = document.getElementById("leagueRankTopTwo");
    const leagueRankAverage = document.getElementById("leagueRankAverage");
    const paletteNodes = [...document.querySelectorAll("[data-palette-node]")];
    const legacyTenMain = legacyTenPanel?.querySelector(".panel-main");
    const legacyTenSide = legacyTenPanel?.querySelector(".panel-side");
    const maradonaSide = maradonaPanel?.querySelector(".panel-side");
    const maradonaPortraitWrap = maradonaPanel?.querySelector(".player-portrait-wrap");
    const romarioSide = romarioPanel?.querySelector(".panel-side");
    const romarioPortraitWrap = romarioPanel?.querySelector(".player-portrait-wrap");
    const rivaldoSide = rivaldoPanel?.querySelector(".panel-side");
    const rivaldoPortraitWrap = rivaldoPanel?.querySelector(".player-portrait-wrap");
    const ronaldinhoSide = ronaldinhoPanel?.querySelector(".panel-side");
    const ronaldinhoPortraitWrap = ronaldinhoPanel?.querySelector(".player-portrait-wrap");
    const messiSide = messiPanel?.querySelector(".panel-side");
    const messiPortraitWrap = messiPanel?.querySelector(".player-portrait-wrap");
    const yamalSide = yamalPanel?.querySelector(".panel-side");
    const yamalPortraitWrap = yamalPanel?.querySelector(".player-portrait-wrap");
    let kitSeasonSteps = [];
    let kitArchiveActivated = false;
    let activeKitIndex = 0;
    let kitActivationScrollY = null;
    let crestEraSteps = [];
    let crestArchiveActivated = false;
    let activeCrestIndex = 0;
    let crestActivationScrollY = null;
    let trophyScatterPointsList = [];
    let trophyScatterLabels = [];
    let trophyScatterChips = [];
    let activeTrophyScatterIndex = 4;
    let leagueRankBars = [];
    let activeLeagueRankIndex = 0;
    let legacyTenAnchor = null;
    let activePaletteColor = "red";

    const kitArchiveData = [
      ["1899", "split", "The first Barcelona shirt establishes the club's earliest blaugrana split as a point of origin.", "First Jersey", "/Users/eddy/Desktop/Barca Jersey/1899.png"],
      ["1982/89", "classic", "A long Meyba-era home shirt establishes the archive before the late-1980s transition.", "Early Meyba era", "/Users/eddy/Desktop/Barca Jersey/82_89.png"],
      ["1989/92", "split", "One home shirt spans the late 1980s into the early 1990s, anchoring the archive's opening identity.", "Foundational split", "/Users/eddy/Desktop/Barca Jersey/89_92.png"],
      ["1992/95", "wide", "A single early-1990s design carries across multiple seasons as the classic vertical format settles in.", "Early stripes", "/Users/eddy/Desktop/Barca Jersey/92_95.png"],
      ["1995/97", "balanced", "The Kappa-era shirt holds across two seasons, keeping the same broad red-blue structure.", "Kappa era", "/Users/eddy/Desktop/Barca Jersey/95_97.png"],
      ["1997/98", "balanced", "The Nike transition introduces a cleaner, more compressed stripe geometry.", "Nike era start", "/Users/eddy/Desktop/Barca Jersey/97_98.png"],
      ["1998/99", "balanced", "Late-1990s kits maintain symmetry while polishing the overall geometry.", "Nike era", "/Users/eddy/Desktop/Barca Jersey/98_99.png"],
      ["1999/00", "split", "A return to split logic feels archival, almost like a centenary gesture.", "Centenary mood", "/Users/eddy/Desktop/Barca Jersey/99_00.png"],
      ["2000/01", "balanced", "The home identity returns to a dependable striped format.", "Stripe reset", "/Users/eddy/Desktop/Barca Jersey/00_01.png"],
      ["2001/02", "balanced", "Even stripe pacing makes the shirt read clearly from distance.", "Stripe reset", "/Users/eddy/Desktop/Barca Jersey/01_02.png"],
      ["2002/03", "classic", "Classic verticality becomes the dominant visual language again.", "Classic stripes", "/Users/eddy/Desktop/Barca Jersey/02_03.png"],
      ["2003/04", "classic", "The shirt stays strict and readable, leaning into pure blaugrana recognition.", "Classic stripes", "/Users/eddy/Desktop/Barca Jersey/03_04.png"],
      ["2004/05", "classic", "Minimal variation, strong continuity, and stable red-blue cadence.", "Classic stripes", "/Users/eddy/Desktop/Barca Jersey/04_05.png"],
      ["2005/06", "classic", "The shirt reads as a textbook version of the modern Barca home kit.", "Classic stripes", "/Users/eddy/Desktop/Barca Jersey/05_06.png"],
      ["2006/07", "narrow", "Stripes narrow and sharpen, making the shirt feel faster and lighter.", "UNICEF era begins", "/Users/eddy/Desktop/Barca Jersey/06_07.png"],
      ["2007/08", "narrow", "A tighter stripe rhythm creates a more contemporary visual texture.", "UNICEF era", "/Users/eddy/Desktop/Barca Jersey/07_08.png"],
      ["2008/09", "modern", "The Guardiola-era shirt feels iconic because the visual system and the football align.", "Guardiola peak", "/Users/eddy/Desktop/Barca Jersey/08_09.png"],
      ["2009/10", "modern", "The blaugrana language becomes globally legible through repetition and success.", "Guardiola peak", "/Users/eddy/Desktop/Barca Jersey/09_10.png"],
      ["2010/11", "modern", "A very clean stripe structure underlines one of Barca's defining seasons.", "Guardiola peak", "/Users/eddy/Desktop/Barca Jersey/10_11.png"],
      ["2011/12", "bold", "Broader stripe blocks make the shirt feel stronger and more graphic.", "Late peak era", "/Users/eddy/Desktop/Barca Jersey/11_12.png"],
      ["2012/13", "bold", "The pattern remains bold, but with less reliance on narrow segmentation.", "Late peak era", "/Users/eddy/Desktop/Barca Jersey/12_13.png"],
      ["2013/14", "centered", "A stronger central axis gives the shirt a more poster-like composition.", "Central emphasis", "/Users/eddy/Desktop/Barca Jersey/13_14.png"],
      ["2014/15", "centered", "The home kit pushes visual mass toward the middle without losing identity.", "Treble-era boldness", "/Users/eddy/Desktop/Barca Jersey/14_15.png"],
      ["2015/16", "banded", "Stripe logic loosens, testing how far the home look can stretch while staying Barca.", "Experimental phase", "/Users/eddy/Desktop/Barca Jersey/15_16.png"],
      ["2016/17", "banded", "The shirt continues to play with block density and stripe interruption.", "Experimental phase", "/Users/eddy/Desktop/Barca Jersey/16_17.png"],
      ["2017/18", "mixed", "More varied spacing creates a looser, contemporary stripe field.", "Mixed stripe study", "/Users/eddy/Desktop/Barca Jersey/17_18.png"],
      ["2018/19", "mixed", "Blue and red fields remain dominant, but spacing becomes less rigid.", "Mixed stripe study", "/Users/eddy/Desktop/Barca Jersey/18_19.png"],
      ["2019/20", "check", "A more grid-like interpretation breaks the pure vertical rule.", "Grid experiment", "/Users/eddy/Desktop/Barca Jersey/19_20.png"],
      ["2020/21", "quarter", "The shirt leans into segmented composition rather than uninterrupted stripes.", "Quartered logic", "/Users/eddy/Desktop/Barca Jersey/20_21.png"],
      ["2021/22", "split-modern", "Blocks return, but with modern asymmetry and sharper contrast.", "Modern split", "/Users/eddy/Desktop/Barca Jersey/21_22.png"],
      ["2022/23", "narrow", "The shirt re-centers vertical rhythm in a more contemporary narrow cadence.", "Return to stripes", "/Users/eddy/Desktop/Barca Jersey/22_23.png"],
      ["2023/24", "classic", "A more familiar stripe language reconnects the shirt to historical continuity.", "Return to stripes", "/Users/eddy/Desktop/Barca Jersey/23_24.png"],
      ["2024/25", "classic", "The archive settles back into a classic reading of blaugrana identity.", "Continuity", "/Users/eddy/Desktop/Barca Jersey/24_25.png"],
      ["2025/26", "split-bold", "The latest shirt reads like a bold remix of classic split and stripe traditions.", "Current season", "/Users/eddy/Desktop/Barca Jersey/25_26.png"]
    ];

    const crestArchiveData = [
      ["1899-1910", "Founding emblem", "The first emblem still behaves like a civic seal, tying the club directly to the city's heraldic memory.", "Origins", "/Users/eddy/Desktop/Barca Logo/1899-1910.png"],
      ["1910-1920", "First shield", "The identity begins to compress into a recognizable football crest, replacing the founding seal with a shield logic.", "Shield takes shape", "/Users/eddy/Desktop/Barca Logo/1910-1920.png"],
      ["1920-1936", "Shield refinement", "The crest becomes cleaner and more legible, establishing the upper cross-and-stripes split more clearly.", "Pre-war refinement", "/Users/eddy/Desktop/Barca Logo/1920-1936.png"],
      ["1936-1941", "Wartime version", "The badge changes under political pressure, but the core split structure remains readable.", "Civil war era", "/Users/eddy/Desktop/Barca Logo/1936-1941.png"],
      ["1941-1949", "C. F. B.", "Castilian initials mark a forced linguistic shift, showing how even a crest can record political intervention.", "Initials altered", "/Users/eddy/Desktop/Barca Logo/1941-1949.png"],
      ["1949-1960", "Postwar crest", "The shield regains confidence and symmetry, moving toward the modern badge most supporters recognize.", "Postwar return", "/Users/eddy/Desktop/Barca Logo/1949-1960.png"],
      ["1960-1974", "Graphic simplification", "Contours sharpen and interior zones simplify, helping the crest read more easily across print and fabric.", "Streamlined form", "/Users/eddy/Desktop/Barca Logo/1960-1974.png"],
      ["1974-1975", "F.C.B. return", "The initials shift back toward Catalan identity, making the badge itself part of the club's cultural argument.", "Identity restored", "/Users/eddy/Desktop/Barca Logo/1974-1975.png"],
      ["1975-2002", "Modern precedent", "This long-running version becomes the visual bridge between historical symbolism and modern global branding.", "Modern classic", "/Users/eddy/Desktop/Barca Logo/1975-2002.png"],
      ["2002-Today", "Current crest", "The present badge keeps the historic grammar but smooths it for a contemporary, globally legible identity.", "Current crest", "/Users/eddy/Desktop/Barca Logo/2002-Today.png"]
    ];

    const contributionData = [
      { name: "Maradona", goals: 38, assists: 23 },
      { name: "Romario", goals: 39, assists: 17 },
      { name: "Rivaldo", goals: 135, assists: 65 },
      { name: "Ronaldinho", goals: 99, assists: 83 },
      { name: "Messi", goals: 672, assists: 303 },
      { name: "Yamal", goals: 46, assists: 50 }
    ].map((player) => ({
      ...player,
      total: player.goals + player.assists
    }));

    const trophyScatterData = [
      {
        name: "Maradona",
        short: "DM",
        era: "1982-1984",
        apps: 58,
        trophies: 3,
        accent: "#df547c",
        accentDeep: "#a50044",
        note: "Short spell, immediate silverware.",
        copy: "Maradona sits in the compact-start corner: few Barcelona appearances, but three trophies packed into two charged seasons.",
        labelX: "1.8rem",
        labelY: "0.9rem"
      },
      {
        name: "Romario",
        short: "R",
        era: "1993-1995",
        apps: 65,
        trophies: 2,
        accent: "#78adff",
        accentDeep: "#004d98",
        note: "Brief peak, title-winning impact.",
        copy: "Romario is the ruthless short-burst point: a small appearance total with the trophy return of a decisive Dream Team finisher.",
        labelX: "2.2rem",
        labelY: "2.3rem"
      },
      {
        name: "Rivaldo",
        short: "RV",
        era: "1997-2002",
        apps: 247,
        trophies: 4,
        accent: "#d94c78",
        accentDeep: "#7f1239",
        note: "Heavy usage in a leaner trophy era.",
        copy: "Rivaldo moves right without climbing far up: a huge role across difficult years, with silverware arriving less often than the workload deserved.",
        labelX: "1.4rem",
        labelY: "1.1rem"
      },
      {
        name: "Ronaldinho",
        short: "R10",
        era: "2003-2008",
        apps: 205,
        trophies: 5,
        accent: "#7fb8ff",
        accentDeep: "#004d98",
        note: "Rebuild point: medium apps, major reset.",
        copy: "Ronaldinho sits above the early-cluster group: enough years to rebuild the club's mood, enough trophies to make that rebirth visible.",
        labelX: "2.2rem",
        labelY: "-0.2rem"
      },
      {
        name: "Messi",
        short: "LM",
        era: "2004-2021",
        apps: 778,
        trophies: 35,
        accent: "#f2c14e",
        accentDeep: "#d69b18",
        note: "Peak outlier: high appearances, high trophies.",
        copy: "Messi stretches the scale: the only point combining extreme longevity with trophy dominance.",
        labelX: "-2.8rem",
        labelY: "1.2rem"
      },
      {
        name: "Yamal",
        short: "LY",
        era: "2022-present",
        apps: 146,
        trophies: 5,
        accent: "#8cc3ff",
        accentDeep: "#0066bd",
        note: "Young trajectory already climbing.",
        copy: "Yamal is still early on the x-axis, but his trophy position already separates him from a normal teenage starting point.",
        labelX: "1.8rem",
        labelY: "-0.6rem"
      }
    ];

    const leagueRankData = [
      { season: "1980-81", rank: 5, points: 41 },
      { season: "1981-82", rank: 2, points: 45 },
      { season: "1982-83", rank: 4, points: 44 },
      { season: "1983-84", rank: 3, points: 48 },
      { season: "1984-85", rank: 1, points: 53 },
      { season: "1985-86", rank: 2, points: 45 },
      { season: "1986-87", rank: 2, points: 49 },
      { season: "1987-88", rank: 6, points: 39 },
      { season: "1988-89", rank: 2, points: 57 },
      { season: "1989-90", rank: 3, points: 51 },
      { season: "1990-91", rank: 1, points: 57 },
      { season: "1991-92", rank: 1, points: 55 },
      { season: "1992-93", rank: 1, points: 58 },
      { season: "1993-94", rank: 1, points: 56 },
      { season: "1994-95", rank: 4, points: 46 },
      { season: "1995-96", rank: 3, points: 80 },
      { season: "1996-97", rank: 2, points: 90 },
      { season: "1997-98", rank: 1, points: 74 },
      { season: "1998-99", rank: 1, points: 79 },
      { season: "1999-00", rank: 2, points: 64 },
      { season: "2000-01", rank: 4, points: 63 },
      { season: "2001-02", rank: 4, points: 64 },
      { season: "2002-03", rank: 6, points: 56 },
      { season: "2003-04", rank: 2, points: 72 },
      { season: "2004-05", rank: 1, points: 84 },
      { season: "2005-06", rank: 1, points: 82 },
      { season: "2006-07", rank: 2, points: 76 },
      { season: "2007-08", rank: 3, points: 67 },
      { season: "2008-09", rank: 1, points: 87 },
      { season: "2009-10", rank: 1, points: 99 },
      { season: "2010-11", rank: 1, points: 96 },
      { season: "2011-12", rank: 2, points: 91 },
      { season: "2012-13", rank: 1, points: 100 },
      { season: "2013-14", rank: 2, points: 87 },
      { season: "2014-15", rank: 1, points: 94 },
      { season: "2015-16", rank: 1, points: 91 },
      { season: "2016-17", rank: 2, points: 90 },
      { season: "2017-18", rank: 1, points: 93 },
      { season: "2018-19", rank: 1, points: 87 },
      { season: "2019-20", rank: 2, points: 82 },
      { season: "2020-21", rank: 3, points: 79 },
      { season: "2021-22", rank: 2, points: 73 },
      { season: "2022-23", rank: 1, points: 88 },
      { season: "2023-24", rank: 2, points: 85 },
      { season: "2024-25", rank: 1, points: 88 }
    ];

    function setActivePaletteNode(colorKey) {
      activePaletteColor = colorKey;
      paletteNodes.forEach((node) => {
        const isActive = node.dataset.colorKey === colorKey;
        node.classList.toggle("is-expanded", isActive);
        node.setAttribute("aria-expanded", String(isActive));
      });
    }

    function initColorsOpening() {
      if (!colorsOpening || !paletteNodes.length) return;

      paletteNodes.forEach((node) => {
        const colorKey = node.dataset.colorKey;
        node.addEventListener("click", () => {
          setActivePaletteNode(colorKey);
        });
        node.addEventListener("pointerenter", () => {
          setActivePaletteNode(colorKey);
        });
      });
      setActivePaletteNode(activePaletteColor);
    }

    function getKitPattern(style) {
      const patterns = {
        split: "linear-gradient(90deg, #a50044 0 50%, #004d98 50% 100%)",
        wide: "repeating-linear-gradient(90deg, #a50044 0 24%, #004d98 24% 48%)",
        balanced: "repeating-linear-gradient(90deg, #a50044 0 19%, #004d98 19% 38%)",
        classic: "linear-gradient(90deg, #a50044 0 16%, #004d98 16% 32%, #a50044 32% 48%, #004d98 48% 64%, #a50044 64% 80%, #004d98 80% 100%)",
        narrow: "repeating-linear-gradient(90deg, #a50044 0 12%, #004d98 12% 24%)",
        modern: "linear-gradient(90deg, #a50044 0 18%, #004d98 18% 36%, #a50044 36% 58%, #004d98 58% 78%, #a50044 78% 100%)",
        bold: "linear-gradient(90deg, #a50044 0 26%, #004d98 26% 50%, #a50044 50% 74%, #004d98 74% 100%)",
        centered: "linear-gradient(90deg, #004d98 0 24%, #a50044 24% 40%, #004d98 40% 60%, #a50044 60% 76%, #004d98 76% 100%)",
        banded: "linear-gradient(180deg, #a50044 0 24%, #004d98 24% 52%, #a50044 52% 76%, #004d98 76% 100%)",
        mixed: "linear-gradient(90deg, #a50044 0 20%, #004d98 20% 28%, #a50044 28% 52%, #004d98 52% 72%, #a50044 72% 84%, #004d98 84% 100%)",
        check: "linear-gradient(90deg, #a50044 0 50%, #004d98 50% 100%), linear-gradient(180deg, rgba(255,255,255,0.14) 0 50%, rgba(0,0,0,0.04) 50% 100%)",
        quarter: "linear-gradient(90deg, #a50044 0 50%, #004d98 50% 100%), linear-gradient(180deg, transparent 0 50%, rgba(255,255,255,0.1) 50% 100%)",
        "split-modern": "linear-gradient(90deg, #a50044 0 42%, #004d98 42% 58%, #a50044 58% 100%)",
        "split-bold": "linear-gradient(90deg, #a50044 0 34%, #004d98 34% 66%, #a50044 66% 100%)"
      };
      return patterns[style] || patterns.classic;
    }

    function setActiveKit(index) {
      activeKitIndex = index;
      const [season, style, note, tag, imageSrc] = kitArchiveData[index];
      kitPreviewSeason.textContent = season;
      kitPreviewTag.textContent = tag;
      kitPreviewNote.textContent = note;
      kitPreviewMeta.textContent = "Home shirt / scroll archive";
      kitPreviewShirt.style.background = getKitPattern(style);

      if (imageSrc) {
        kitPreviewPhoto.src = imageSrc;
        kitPreviewPhoto.classList.add("is-visible");
        kitPreviewPhoto.classList.toggle("is-heritage", season === "1899");
        kitPreviewPhoto.classList.toggle("is-compact", season === "1995/97");
        kitPreviewShirt.style.display = "none";
      } else {
        kitPreviewPhoto.removeAttribute("src");
        kitPreviewPhoto.classList.remove("is-visible");
        kitPreviewPhoto.classList.remove("is-heritage");
        kitPreviewPhoto.classList.remove("is-compact");
        kitPreviewShirt.style.display = "block";
      }

      document.querySelectorAll(".kit-season-step").forEach((step, stepIndex) => {
        step.classList.toggle("is-active", stepIndex === index);
      });

      updateKitTimelineTransform();
    }

    function jumpToKit(index) {
      if (!kitArchivePanel || !kitSeasonSteps.length) {
        setActiveKit(index);
        return;
      }

      const { holdDistance, seasonTravel } = getKitArchiveMetrics();
      const panelRect = kitArchivePanel.getBoundingClientRect();
      const panelTopAbs = window.scrollY + panelRect.top;
      const panelBottomAbs = panelTopAbs + kitArchivePanel.offsetHeight;
      const withinPanel = panelRect.top < window.innerHeight && panelRect.bottom > 0;

      if (withinPanel) {
        kitArchiveActivated = true;
        kitActivationScrollY = window.scrollY - holdDistance - seasonTravel * index;
        setActiveKit(index);
        return;
      }

      const targetScrollY = Math.min(
        Math.max(panelTopAbs + 2, 0),
        Math.max(panelBottomAbs - window.innerHeight, panelTopAbs)
      );

      kitArchiveActivated = true;
      kitActivationScrollY = targetScrollY - holdDistance - seasonTravel * index;
      setActiveKit(index);

      window.scrollTo({
        top: targetScrollY,
        behavior: "smooth"
      });
    }

    function buildKitArchive() {
      const fragment = document.createDocumentFragment();

      kitArchiveData.forEach(([season, style, note, tag], index) => {
        const step = document.createElement("div");
        step.className = "kit-season-step";
        step.dataset.index = index;
        step.tabIndex = 0;
        step.setAttribute("role", "button");
        step.setAttribute("aria-label", `Jump to ${season} home kit`);
        step.innerHTML = `
          <div class="kit-season-dot"></div>
          <div class="kit-season-label">
            <div class="kit-season-year">${season}</div>
            <div class="kit-season-style">${tag}</div>
          </div>
        `;
        step.addEventListener("click", () => {
          jumpToKit(index);
        });
        step.addEventListener("keydown", (event) => {
          if (event.key === "Enter" || event.key === " ") {
            event.preventDefault();
            jumpToKit(index);
          }
        });
        fragment.appendChild(step);
      });

      kitSeasonList.innerHTML = "";
      kitSeasonList.appendChild(fragment);
      setActiveKit(0);

      const steps = [...document.querySelectorAll(".kit-season-step")];
      kitSeasonSteps = steps;
      syncKitArchiveHeight();
      updateActiveKitFromScroll();
    }

    function setActiveCrest(index) {
      activeCrestIndex = index;
      const [era, tag, note, meta, imageSrc] = crestArchiveData[index];
      crestPreviewEra.textContent = era;
      crestPreviewTag.textContent = tag;
      crestPreviewNote.textContent = note;
      crestPreviewMeta.textContent = `Crest archive / ${meta}`;
      crestPreviewPhoto.src = imageSrc;

      document.querySelectorAll(".crest-era-step").forEach((step, stepIndex) => {
        step.classList.toggle("is-active", stepIndex === index);
      });

      updateCrestTimelineTransform();
    }

    function buildCrestArchive() {
      const fragment = document.createDocumentFragment();

      crestArchiveData.forEach(([era, tag], index) => {
        const step = document.createElement("div");
        step.className = "crest-era-step";
        step.dataset.index = index;
        step.innerHTML = `
          <div class="crest-era-dot">${String(index + 1).padStart(2, "0")}</div>
          <div class="crest-era-drop" aria-hidden="true"></div>
          <div class="crest-era-copy">
            <div class="crest-era-kicker">Year</div>
            <div class="crest-era-label">
              <div class="crest-era-year">${era}</div>
              <div class="crest-era-style">${tag}</div>
            </div>
            <div class="crest-era-rule" aria-hidden="true"></div>
          </div>
        `;
        fragment.appendChild(step);
      });

      crestEraList.innerHTML = "";
      crestEraList.appendChild(fragment);
      crestEraSteps = [...document.querySelectorAll(".crest-era-step")];
      setActiveCrest(0);
      updateActiveCrestFromScroll();
    }

    function buildContributionRain() {
      if (!contributionGrid) return;

      contributionGrid.innerHTML = "";
      const fragment = document.createDocumentFragment();

      contributionData.forEach((player, index) => {
        const card = document.createElement("article");
        card.className = "contribution-card";

        const rainCount = Math.max(3, Math.round(player.total / 20));
        const pileCount = Math.max(4, Math.round(player.total / 25));

        const rainBalls = Array.from({ length: rainCount }, (_, ballIndex) => {
          const x = 16 + ((ballIndex * 17 + index * 11) % 68);
          const delay = ((ballIndex * 0.37 + index * 0.22) % 4.2).toFixed(2);
          const duration = (4.7 + ((ballIndex + index) % 5) * 0.38).toFixed(2);
          return `<span class="rain-ball" style="--x:${x}%; --delay:${delay}s; --duration:${duration}s;"></span>`;
        }).join("");

        const binBalls = Array.from({ length: pileCount }, () => '<span class="bin-ball"></span>').join("");

        card.innerHTML = `
          <div class="contribution-player">${player.name}</div>
          <div class="contribution-total">${player.total}</div>
          <div class="contribution-breakdown">${player.goals} goals + ${player.assists} assists</div>
          <div class="ball-rain" aria-label="${player.name} contribution rain">
            ${rainBalls}
            <div class="ball-rain-bin">${binBalls}</div>
          </div>
        `;

        fragment.appendChild(card);
      });

      contributionGrid.appendChild(fragment);
    }

    function setActiveTrophyScatter(index) {
      if (!trophyScatterData.length || !trophyScatterPlot) return;

      const nextIndex = clamp(index, 0, trophyScatterData.length - 1);
      const item = trophyScatterData[nextIndex];
      const xPercent = (item.apps / 800) * 100;
      const yPercent = (item.trophies / 40) * 100;
      const appsPerTrophy = item.apps / Math.max(item.trophies, 1);

      activeTrophyScatterIndex = nextIndex;
      trophyScatterPlot.style.setProperty("--focus-x", `${xPercent.toFixed(2)}%`);
      trophyScatterPlot.style.setProperty("--focus-y", `${yPercent.toFixed(2)}%`);
      trophyDetailPanel?.style.setProperty("--active", item.accent);
      trophyDetailPanel?.style.setProperty("--active-soft", `${item.accent}24`);

      trophyScatterPointsList.forEach((point, pointIndex) => {
        point.classList.toggle("is-active", pointIndex === nextIndex);
      });
      trophyScatterLabels.forEach((label, labelIndex) => {
        label.classList.toggle("is-active", labelIndex === nextIndex);
      });
      trophyScatterChips.forEach((chip, chipIndex) => {
        chip.classList.toggle("is-active", chipIndex === nextIndex);
      });

      if (trophyDetailName) trophyDetailName.textContent = item.name;
      if (trophyDetailEra) trophyDetailEra.textContent = item.era;
      if (trophyDetailApps) trophyDetailApps.textContent = item.apps;
      if (trophyDetailTrophies) trophyDetailTrophies.textContent = item.trophies;
      if (trophyDetailRate) trophyDetailRate.textContent = appsPerTrophy.toFixed(1);
      if (trophyDetailShare) trophyDetailShare.textContent = `${Math.round((item.trophies / 40) * 100)}%`;
      if (trophyDetailCopy) trophyDetailCopy.textContent = item.copy;
      if (trophyDetailNote) trophyDetailNote.textContent = item.note;
    }

    function buildTrophyScatter() {
      if (!trophyScatterPoints || !trophyPlayerRail) return;

      const pointFragment = document.createDocumentFragment();
      const chipFragment = document.createDocumentFragment();

      trophyScatterPoints.innerHTML = "";
      trophyPlayerRail.innerHTML = "";

      trophyScatterData.forEach((player, index) => {
        const xPercent = (player.apps / 800) * 100;
        const yPercent = (player.trophies / 40) * 100;
        const bubbleSize = 1.15 + (player.trophies / 40) * 2.1;
        const point = document.createElement("button");
        const label = document.createElement("span");
        const chip = document.createElement("button");

        point.type = "button";
        point.className = "trophy-point";
        point.style.setProperty("--x", `${xPercent.toFixed(2)}%`);
        point.style.setProperty("--y", `${yPercent.toFixed(2)}%`);
        point.style.setProperty("--bubble-size", `${bubbleSize.toFixed(2)}rem`);
        point.style.setProperty("--accent", player.accent);
        point.style.setProperty("--accent-deep", player.accentDeep);
        point.style.setProperty("--accent-soft", `${player.accent}24`);
        point.setAttribute("aria-label", `${player.name}: ${player.apps} appearances, ${player.trophies} trophies`);
        point.innerHTML = `<span>${player.short}</span>`;
        point.addEventListener("pointerenter", () => setActiveTrophyScatter(index));
        point.addEventListener("focus", () => setActiveTrophyScatter(index));
        point.addEventListener("click", () => setActiveTrophyScatter(index));

        label.className = "trophy-point-label";
        label.textContent = player.name;
        label.style.setProperty("--x", `${xPercent.toFixed(2)}%`);
        label.style.setProperty("--y", `${yPercent.toFixed(2)}%`);
        label.style.setProperty("--label-x", player.labelX);
        label.style.setProperty("--label-y", player.labelY);

        chip.type = "button";
        chip.className = "trophy-player-chip";
        chip.textContent = player.name;
        chip.style.setProperty("--active", player.accent);
        chip.style.setProperty("--active-soft", `${player.accent}24`);
        chip.addEventListener("pointerenter", () => setActiveTrophyScatter(index));
        chip.addEventListener("focus", () => setActiveTrophyScatter(index));
        chip.addEventListener("click", () => setActiveTrophyScatter(index));

        pointFragment.appendChild(point);
        pointFragment.appendChild(label);
        chipFragment.appendChild(chip);
      });

      trophyScatterPoints.appendChild(pointFragment);
      trophyPlayerRail.appendChild(chipFragment);
      trophyScatterPointsList = [...trophyScatterPoints.querySelectorAll(".trophy-point")];
      trophyScatterLabels = [...trophyScatterPoints.querySelectorAll(".trophy-point-label")];
      trophyScatterChips = [...trophyPlayerRail.querySelectorAll(".trophy-player-chip")];
      setActiveTrophyScatter(activeTrophyScatterIndex);
    }

    function formatOrdinal(value) {
      const suffix = value % 10 === 1 && value % 100 !== 11
        ? "st"
        : value % 10 === 2 && value % 100 !== 12
          ? "nd"
          : value % 10 === 3 && value % 100 !== 13
            ? "rd"
            : "th";

      return `${value}${suffix}`;
    }

    function getLeagueRankEra(item) {
      const year = Number(item.season.slice(0, 4));

      if (year <= 1989) return "Pre-Dream Team reset";
      if (year <= 1994) return "Cruyff's Dream Team";
      if (year <= 2003) return "Rebuild into Europe";
      if (year <= 2011) return "Ronaldinho to Guardiola";
      if (year <= 2019) return "Messi-era control";
      return "Post-Messi reset";
    }

    function getLeagueRankStatus(rank) {
      if (rank === 1) return "League champion";
      if (rank === 2) return "Runner-up";
      if (rank === 3) return "Third-place finish";
      if (rank === 4) return "Top-four finish";
      return "Outside top four";
    }

    function getLeagueRankToneClass(rank) {
      if (rank === 1) return "is-rank-champion";
      if (rank === 2) return "is-rank-runner-up";
      if (rank === 3) return "is-rank-third-place";
      return "is-rank-lower-finish";
    }

    function getLeagueRankDetail(item) {
      const status = getLeagueRankStatus(item.rank).toLowerCase();
      const era = getLeagueRankEra(item);
      const pointNote = Number.isFinite(item.points) ? `${item.points} league points` : "final points pending";

      if (item.rank === 1) {
        return `${item.season} lands on the top line: a ${status} in the ${era} phase, with ${pointNote}.`;
      }

      if (item.rank === 2) {
        return `${item.season} stays in title-race territory as a ${status}, closing the season with ${pointNote}.`;
      }

      return `${item.season} drops below the title line during the ${era} phase, finishing ${formatOrdinal(item.rank)} with ${pointNote}.`;
    }

    function setActiveLeagueRank(index) {
      if (!leagueRankData.length) return;

      const nextIndex = clamp(index, 0, leagueRankData.length - 1);
      const item = leagueRankData[nextIndex];
      activeLeagueRankIndex = nextIndex;

      leagueRankBars.forEach((bar, barIndex) => {
        bar.classList.toggle("is-active", barIndex === nextIndex);
      });

      leagueRankSection?.classList.remove(
        "is-rank-champion",
        "is-rank-runner-up",
        "is-rank-third-place",
        "is-rank-lower-finish"
      );
      leagueRankSection?.classList.add(getLeagueRankToneClass(item.rank));

      if (leagueRankSeason) leagueRankSeason.textContent = item.season;
      if (leagueRankPosition) leagueRankPosition.textContent = formatOrdinal(item.rank);
      if (leagueRankStatus) leagueRankStatus.textContent = getLeagueRankStatus(item.rank);
      if (leagueRankDetail) leagueRankDetail.textContent = getLeagueRankDetail(item);
      if (leagueRankEra) leagueRankEra.textContent = getLeagueRankEra(item);
    }

    function buildLeagueRankChart() {
      if (!leagueRankChart) return;

      const maxRank = Math.max(...leagueRankData.map((item) => item.rank));
      const titles = leagueRankData.filter((item) => item.rank === 1).length;
      const topTwo = leagueRankData.filter((item) => item.rank <= 2).length;
      const averageRank = leagueRankData.reduce((sum, item) => sum + item.rank, 0) / leagueRankData.length;
      const fragment = document.createDocumentFragment();

      leagueRankChart.innerHTML = "";
      leagueRankChart.style.setProperty("--rank-count", leagueRankData.length);

      leagueRankData.forEach((item, index) => {
        const startYear = Number(item.season.slice(0, 4));
        const bar = document.createElement("button");
        const normalizedHeight = Math.max(8, ((maxRank - item.rank) / Math.max(maxRank - 1, 1)) * 100);

        bar.type = "button";
        bar.className = [
          "league-rank-bar",
          item.rank === 1 ? "is-champion" : "",
          item.rank === 2 ? "is-runner-up" : "",
          item.rank === 3 ? "is-third-place" : "",
          item.rank >= 4 ? "is-lower-finish" : "",
          startYear % 10 === 0 || index === leagueRankData.length - 1 ? "is-decade" : ""
        ].filter(Boolean).join(" ");
        bar.style.setProperty("--bar-height", `${normalizedHeight.toFixed(2)}%`);
        bar.setAttribute("aria-label", `${item.season}: ${formatOrdinal(item.rank)} in La Liga`);
        bar.innerHTML = `
          <span class="league-rank-bar-fill"></span>
          <span class="league-rank-year">${String(startYear).slice(2)}</span>
        `;
        bar.addEventListener("click", () => {
          const maxTravel = Math.max(leagueRankSection.offsetHeight - window.innerHeight, 1);
          const progress = leagueRankData.length > 1 ? index / (leagueRankData.length - 1) : 0;
          window.scrollTo({
            top: leagueRankSection.offsetTop + maxTravel * progress,
            behavior: "smooth"
          });
        });

        fragment.appendChild(bar);
      });

      leagueRankChart.appendChild(fragment);
      leagueRankBars = [...leagueRankChart.querySelectorAll(".league-rank-bar")];

      if (leagueRankTitles) leagueRankTitles.textContent = titles;
      if (leagueRankTopTwo) leagueRankTopTwo.textContent = topTwo;
      if (leagueRankAverage) leagueRankAverage.textContent = averageRank.toFixed(1);

      setActiveLeagueRank(activeLeagueRankIndex);
    }

    function updateLeagueRankStickyState(rect) {
      if (!leagueRankSticky) return;

      const sectionActive = rect.top <= 0 && rect.bottom >= window.innerHeight;
      const sectionPassed = rect.bottom < window.innerHeight;

      leagueRankSticky.style.left = "0";
      leagueRankSticky.style.right = "0";
      leagueRankSticky.style.width = "100%";

      if (sectionActive) {
        leagueRankSticky.style.position = "fixed";
        leagueRankSticky.style.top = "0";
        leagueRankSticky.style.bottom = "auto";
        leagueRankSticky.style.zIndex = "5";
        return;
      }

      leagueRankSticky.style.position = "absolute";
      leagueRankSticky.style.zIndex = "1";

      if (sectionPassed) {
        leagueRankSticky.style.top = "auto";
        leagueRankSticky.style.bottom = "0";
      } else {
        leagueRankSticky.style.top = "0";
        leagueRankSticky.style.bottom = "auto";
      }
    }

    function updateLeagueRankScroll() {
      if (!leagueRankSection || !leagueRankData.length) return;

      const rect = leagueRankSection.getBoundingClientRect();
      const maxTravel = Math.max(leagueRankSection.offsetHeight - window.innerHeight, 1);
      const progress = clamp(-rect.top / maxTravel, 0, 1);
      const nextIndex = Math.round(progress * (leagueRankData.length - 1));

      updateLeagueRankStickyState(rect);

      leagueRankSection.style.setProperty("--rank-chart-scale", "1");

      if (nextIndex !== activeLeagueRankIndex) {
        setActiveLeagueRank(nextIndex);
      }
    }

    function updateActiveCrestFromScroll() {
      if (!crestEraSteps.length) return;

      if (!crestArchiveActivated) {
        if (activeCrestIndex !== 0) setActiveCrest(0);
        return;
      }

      if (crestActivationScrollY === null) {
        crestActivationScrollY = window.scrollY;
      }

      const { holdDistance, eraTravel } = getCrestArchiveMetrics();
      const travel = Math.max(window.scrollY - crestActivationScrollY - holdDistance, 0);
      const nextIndex = clamp(Math.floor(travel / eraTravel), 0, crestArchiveData.length - 1);

      if (nextIndex !== activeCrestIndex) {
        setActiveCrest(nextIndex);
      } else {
        updateCrestTimelineTransform();
      }
    }

    function updateCrestTimelineTransform() {
      if (!crestTimelineRail || !crestEraList || !crestEraSteps.length || window.innerWidth <= 768) {
        if (crestEraList) {
          crestEraList.style.transform = "translateX(0px)";
        }
        if (crestTimelineRail) {
          crestTimelineRail.style.setProperty("--crest-guide-x", "50%");
        }
        return;
      }

      const railWidth = crestTimelineRail.clientWidth;
      if (!railWidth) return;

      const activeStep = crestEraSteps[activeCrestIndex];
      if (!activeStep) return;

      const activeCenter = activeStep.offsetLeft + activeStep.offsetWidth / 2;
      const anchorX = railWidth * 0.5;
      const desiredOffset = anchorX - activeCenter;
      const minOffset = Math.min(0, railWidth - crestEraList.scrollWidth);
      const offset = clamp(desiredOffset, minOffset, 0);

      crestEraList.style.transform = `translateX(${offset}px)`;

      const stepCenter = activeStep.offsetLeft + activeStep.offsetWidth / 2 + offset;
      const guideX = clamp(stepCenter, 28, railWidth - 28);
      crestTimelineRail.style.setProperty("--crest-guide-x", `${guideX}px`);
    }

    function getCrestArchiveMetrics() {
      const holdDistance = Math.max(window.innerHeight * 0.34, 240);
      const baseSpacing = crestEraSteps.length > 1
        ? Math.max(crestEraSteps[1].offsetLeft - crestEraSteps[0].offsetLeft, 200)
        : 200;
      const eraTravel = baseSpacing * 0.92;
      const totalTravel = holdDistance + eraTravel * Math.max(crestArchiveData.length - 1, 0);
      return { holdDistance, baseSpacing, eraTravel, totalTravel };
    }

    function syncCrestArchiveHeight() {
      if (!crestPanel || !crestEraSteps.length || window.innerWidth <= 768) {
        if (crestPanel && window.innerWidth <= 768) {
          crestPanel.style.removeProperty("min-height");
        }
        return;
      }

      const { totalTravel } = getCrestArchiveMetrics();
      const requiredHeight = Math.ceil(window.innerHeight + totalTravel + window.innerHeight * 0.55);
      crestPanel.style.minHeight = `${requiredHeight}px`;
    }

    function getKitArchiveMetrics() {
      const holdDistance = Math.max(window.innerHeight * 0.42, 320);
      const baseSpacing = kitSeasonSteps.length > 1
        ? Math.max(kitSeasonSteps[1].offsetTop - kitSeasonSteps[0].offsetTop, 68)
        : 68;
      const seasonTravel = baseSpacing * 1.35;
      const totalTravel = holdDistance + seasonTravel * Math.max(kitArchiveData.length - 1, 0);
      return { holdDistance, baseSpacing, seasonTravel, totalTravel };
    }

    function syncKitArchiveHeight() {
      if (!kitArchivePanel || !kitSeasonSteps.length || window.innerWidth <= 768) {
        if (kitArchivePanel && window.innerWidth <= 768) {
          kitArchivePanel.style.removeProperty("min-height");
        }
        return;
      }

      const { totalTravel } = getKitArchiveMetrics();
      const requiredHeight = Math.ceil(window.innerHeight + totalTravel + window.innerHeight * 1.25);
      kitArchivePanel.style.minHeight = `${requiredHeight}px`;
    }

    function updateActiveKitFromScroll() {
      if (!kitSeasonSteps.length) return;

      if (!kitArchiveActivated) {
        if (activeKitIndex !== 0) setActiveKit(0);
        return;
      }

      if (kitActivationScrollY === null) {
        kitActivationScrollY = window.scrollY;
      }

      const { holdDistance, seasonTravel } = getKitArchiveMetrics();
      const travel = Math.max(window.scrollY - kitActivationScrollY - holdDistance, 0);
      const nextIndex = clamp(Math.floor(travel / seasonTravel), 0, kitArchiveData.length - 1);

      if (nextIndex !== activeKitIndex) {
        setActiveKit(nextIndex);
      }
    }

    function updateKitTimelineTransform() {
      if (!kitTimelineRail || !kitSeasonList || !kitSeasonSteps.length || window.innerWidth <= 768) {
        if (kitSeasonList) {
          kitSeasonList.style.transform = "translateY(0px)";
        }
        return;
      }

      const railHeight = kitTimelineRail.clientHeight;
      if (!railHeight) return;

      const activeStep = kitSeasonSteps[activeKitIndex];
      if (!activeStep) return;

      const activeCenter = activeStep.offsetTop + activeStep.offsetHeight / 2;
      const anchorY = railHeight * 0.72;
      const desiredOffset = anchorY - activeCenter;
      const minOffset = Math.min(0, railHeight - kitSeasonList.scrollHeight);
      const offset = clamp(desiredOffset, minOffset, 0);

      kitSeasonList.style.transform = `translateY(${offset}px)`;
    }

    function clamp(value, min, max) {
      return Math.min(Math.max(value, min), max);
    }

    function easeInOutCubic(value) {
      return value < 0.5
        ? 4 * value * value * value
        : 1 - Math.pow(-2 * value + 2, 3) / 2;
    }

    function updateLegacyTenExit() {
      if (!legacyTenPanel || !maradonaPanel || window.innerWidth <= 768) {
        if (legacyTenPanel) {
          legacyTenPanel.style.setProperty("--legacy-exit-progress", "0");
        }
        if (maradonaPanel) {
          maradonaPanel.style.setProperty("--player-enter-progress", "1");
          maradonaPanel.style.setProperty("--player-side-progress", "1");
          maradonaPanel.style.setProperty("--maradona-side-entry-progress", "1");
        }
        return { exitProgress: 0, playerEnterProgress: 1 };
      }

      const maradonaRect = maradonaPanel.getBoundingClientRect();
      const exitProgress = clamp((window.innerHeight * 0.9 - maradonaRect.top) / (window.innerHeight * 0.74), 0, 1);
      const playerEnterProgress = easeInOutCubic(
        clamp((window.innerHeight * 0.82 - maradonaRect.top) / (window.innerHeight * 0.44), 0, 1)
      );
      const maradonaSideEntryProgress = easeInOutCubic(
        clamp((window.innerHeight * 0.54 - maradonaRect.top) / (window.innerHeight * 0.24), 0, 1)
      );
      legacyTenPanel.style.setProperty("--legacy-exit-progress", exitProgress.toFixed(3));
      maradonaPanel.style.setProperty("--player-enter-progress", playerEnterProgress.toFixed(3));
      maradonaPanel.style.setProperty("--player-side-progress", maradonaSideEntryProgress.toFixed(3));
      maradonaPanel.style.setProperty("--maradona-side-entry-progress", maradonaSideEntryProgress.toFixed(3));
      return { exitProgress, playerEnterProgress };
    }

    function updateMaradonaPortraitPosition() {
      if (!maradonaPanel || !maradonaSide || !maradonaPortraitWrap || window.innerWidth <= 768) {
        if (maradonaSide) {
          maradonaSide.classList.remove("is-fixed", "is-bottom", "is-fade-fixed");
          maradonaSide.style.position = "";
          maradonaSide.style.bottom = "";
          maradonaSide.style.top = "";
          maradonaSide.style.left = "";
          maradonaSide.style.right = "";
          maradonaSide.style.width = "";
          maradonaSide.style.zIndex = "";
        }
        return;
      }

      const sideEntryProgress = parseFloat(
        window.getComputedStyle(maradonaPanel).getPropertyValue("--maradona-side-entry-progress")
      ) || 0;
      const panelRect = maradonaPanel.getBoundingClientRect();

      const romarioRect = romarioPanel?.getBoundingClientRect();
      const transitionProgress = romarioRect
        ? clamp((window.innerHeight * 0.92 - romarioRect.top) / (window.innerHeight * 0.9), 0, 1)
        : 0;

      const shouldStick = panelRect.top <= -(window.innerHeight * 0.16);

      if (transitionProgress <= 0.001 && sideEntryProgress <= 0.001 && !shouldStick) {
        maradonaSide.classList.remove("is-fixed", "is-bottom", "is-fade-fixed");
        maradonaSide.style.visibility = "hidden";
        maradonaSide.style.position = "";
        maradonaSide.style.bottom = "";
        maradonaSide.style.top = "";
        maradonaSide.style.left = "";
        maradonaSide.style.right = "";
        maradonaSide.style.width = "";
        maradonaSide.style.zIndex = "";
        return;
      }

      const sideRect = maradonaSide.getBoundingClientRect();
      const sideRight = Math.max(window.innerWidth - sideRect.right, 0);
      maradonaPanel.style.setProperty("--player-side-right", `${sideRight}px`);
      maradonaPanel.style.setProperty("--maradona-side-width", `${sideRect.width}px`);

      maradonaSide.classList.remove("is-fixed", "is-bottom", "is-fade-fixed");
      maradonaSide.style.visibility = "visible";
      maradonaSide.style.position = "fixed";
      maradonaSide.style.bottom = "0";
      maradonaSide.style.top = "auto";
      maradonaSide.style.left = "auto";
      maradonaSide.style.right = `${sideRight}px`;
      maradonaSide.style.width = `${sideRect.width}px`;
      maradonaSide.style.zIndex = "6";
    }

    function updateMaradonaToRomarioTransition() {
      if (!maradonaPanel || !romarioPanel || window.innerWidth <= 768) {
        if (maradonaPanel) {
          maradonaPanel.style.setProperty("--player-enter-progress", "1");
          maradonaPanel.style.setProperty("--player-side-progress", "1");
        }
        if (romarioPanel) {
          romarioPanel.style.setProperty("--player-enter-progress", "1");
          romarioPanel.style.setProperty("--player-side-progress", "1");
        }
        return { maradonaExitProgress: 0, romarioEnterProgress: 1 };
      }

      const romarioRect = romarioPanel.getBoundingClientRect();
      if (romarioRect.top > window.innerHeight * 0.92) {
        maradonaPanel.style.setProperty("--player-side-progress", "1");
        romarioPanel.style.setProperty("--player-enter-progress", "0");
        romarioPanel.style.setProperty("--player-side-progress", "0");
        romarioPanel.style.setProperty("--player-side-entry-progress", "0");
        return { maradonaExitProgress: 0, romarioEnterProgress: 0 };
      }

      const transitionProgress = clamp(
        (window.innerHeight * 0.92 - romarioRect.top) / (window.innerHeight * 0.9),
        0,
        1
      );
      const maradonaExitProgress = easeInOutCubic(clamp(transitionProgress / 0.84, 0, 1));
      const romarioEnterProgress = easeInOutCubic(clamp((transitionProgress - 0.14) / 0.66, 0, 1));
      const maradonaSideProgress = 1 - easeInOutCubic(clamp((transitionProgress - 0.06) / 0.72, 0, 1));

      maradonaPanel.style.setProperty(
        "--player-enter-progress",
        (1 - maradonaExitProgress).toFixed(3)
      );
      maradonaPanel.style.setProperty(
        "--player-side-progress",
        maradonaSideProgress.toFixed(3)
      );
      romarioPanel.style.setProperty(
        "--player-enter-progress",
        romarioEnterProgress.toFixed(3)
      );
      romarioPanel.style.setProperty(
        "--player-side-progress",
        romarioEnterProgress.toFixed(3)
      );
      romarioPanel.style.setProperty(
        "--player-side-entry-progress",
        romarioEnterProgress.toFixed(3)
      );

      return { maradonaExitProgress, romarioEnterProgress };
    }

    function updateMaradonaFadeLock() {
      return;
    }

    function updateSequentialPlayerTransition(currentPanel, nextPanel) {
      if (!currentPanel || !nextPanel || window.innerWidth <= 768) {
        currentPanel?.style.setProperty("--player-side-progress", "1");
        nextPanel?.style.setProperty("--player-enter-progress", "1");
        nextPanel?.style.setProperty("--player-side-progress", "1");
        nextPanel?.style.setProperty("--player-side-entry-progress", "1");
        const currentSide = currentPanel?.querySelector(".panel-side");
        const nextSide = nextPanel?.querySelector(".panel-side");
        if (currentSide) currentSide.style.visibility = "visible";
        if (nextSide) nextSide.style.visibility = "visible";
        return { currentExitProgress: 0, nextEnterProgress: 1 };
      }

      const currentSide = currentPanel.querySelector(".panel-side");
      const nextSide = nextPanel.querySelector(".panel-side");

      const nextRect = nextPanel.getBoundingClientRect();
      if (nextRect.top > window.innerHeight * 0.92) {
        currentPanel.style.setProperty("--player-side-progress", "1");
        nextPanel.style.setProperty("--player-enter-progress", "0");
        nextPanel.style.setProperty("--player-side-progress", "0");
        nextPanel.style.setProperty("--player-side-entry-progress", "0");
        if (currentSide) currentSide.style.visibility = "visible";
        if (nextSide) nextSide.style.visibility = "visible";
        return { currentExitProgress: 0, nextEnterProgress: 0 };
      }

      const transitionProgress = clamp(
        (window.innerHeight * 0.92 - nextRect.top) / (window.innerHeight * 0.9),
        0,
        1
      );
      const currentExitProgress = easeInOutCubic(clamp(transitionProgress / 0.98, 0, 1));
      const nextEnterProgress = easeInOutCubic(clamp((transitionProgress - 0.16) / 0.62, 0, 1));
      const currentSideProgress = 1 - easeInOutCubic(clamp((transitionProgress - 0.06) / 0.74, 0, 1));

      currentPanel.style.setProperty(
        "--player-enter-progress",
        (1 - currentExitProgress).toFixed(3)
      );
      currentPanel.style.setProperty(
        "--player-side-progress",
        currentSideProgress.toFixed(3)
      );
      nextPanel.style.setProperty(
        "--player-enter-progress",
        nextEnterProgress.toFixed(3)
      );
      nextPanel.style.setProperty(
        "--player-side-progress",
        nextEnterProgress.toFixed(3)
      );
      nextPanel.style.setProperty(
        "--player-side-entry-progress",
        nextEnterProgress.toFixed(3)
      );

      if (currentSide) {
        currentSide.style.visibility = currentSideProgress <= 0.01 ? "hidden" : "visible";
      }
      if (nextSide) {
        nextSide.style.visibility = "visible";
      }

      return { currentExitProgress, nextEnterProgress };
    }

    function updateRomarioToRivaldoTransition() {
      const { currentExitProgress, nextEnterProgress } = updateSequentialPlayerTransition(
        romarioPanel,
        rivaldoPanel
      );
      return { romarioExitProgress: currentExitProgress, rivaldoEnterProgress: nextEnterProgress };
    }

    function updateRomarioFadeLock() {
      return;
    }

    function updateRivaldoToRonaldinhoTransition() {
      const { currentExitProgress, nextEnterProgress } = updateSequentialPlayerTransition(
        rivaldoPanel,
        ronaldinhoPanel
      );
      return {
        rivaldoExitProgress: currentExitProgress,
        ronaldinhoEnterProgress: nextEnterProgress
      };
    }

    function updateRivaldoFadeLock() {
      return;
    }

    function updateRonaldinhoToMessiTransition() {
      const { currentExitProgress, nextEnterProgress } = updateSequentialPlayerTransition(
        ronaldinhoPanel,
        messiPanel
      );
      return { ronaldinhoExitProgress: currentExitProgress, messiEnterProgress: nextEnterProgress };
    }

    function updateRonaldinhoFadeLock() {
      return;
    }

    function updateMessiToYamalTransition() {
      const { currentExitProgress, nextEnterProgress } = updateSequentialPlayerTransition(
        messiPanel,
        yamalPanel
      );
      return { messiExitProgress: currentExitProgress, yamalEnterProgress: nextEnterProgress };
    }

    function updateMessiFadeLock() {
      return;
    }

    function updatePlayerPortraitPosition(panel, side, portraitWrap, sideVarPrefix, nextPanel = null) {
      if (!panel || !side || !portraitWrap || window.innerWidth <= 768) {
        if (side) {
          side.classList.remove("is-fixed", "is-bottom");
          side.style.position = "";
          side.style.bottom = "";
          side.style.top = "";
          side.style.left = "";
          side.style.right = "";
          side.style.width = "";
          side.style.zIndex = "";
        }
        panel?.style.removeProperty("--player-side-right");
        panel?.style.removeProperty(`--${sideVarPrefix}-side-width`);
        return;
      }

      const enterProgress = parseFloat(
        window.getComputedStyle(panel).getPropertyValue("--player-enter-progress")
      ) || 0;
      const nextRect = nextPanel?.getBoundingClientRect();
      const transitionProgress = nextRect
        ? clamp((window.innerHeight * 0.92 - nextRect.top) / (window.innerHeight * 0.9), 0, 1)
        : 0;
      const currentSideRect = side.getBoundingClientRect();
      const sideRight = Math.max(window.innerWidth - currentSideRect.right, 0);
      const handoffStart = 0.68;
      const handoffEnd = 0.96;
      const handoffProgress = easeInOutCubic(
        clamp((enterProgress - handoffStart) / (handoffEnd - handoffStart), 0, 1)
      );

      if (transitionProgress > 0.001) {
        panel.style.setProperty("--player-side-right", `${sideRight}px`);
        panel.style.setProperty(`--${sideVarPrefix}-side-width`, `${currentSideRect.width}px`);
        side.classList.remove("is-fixed", "is-bottom");
        side.style.position = "fixed";
        side.style.top = "auto";
        side.style.bottom = "0";
        side.style.left = "auto";
        side.style.right = `${sideRight}px`;
        side.style.width = `${currentSideRect.width}px`;
        side.style.zIndex = "7";
        return;
      }

      if (handoffProgress > 0.001) {
        const naturalTop = currentSideRect.top;
        const targetTop = Math.max(window.innerHeight - currentSideRect.height, 0);
        const interpolatedTop = naturalTop + (targetTop - naturalTop) * handoffProgress;

        panel.style.setProperty("--player-side-right", `${sideRight}px`);
        panel.style.setProperty(`--${sideVarPrefix}-side-width`, `${currentSideRect.width}px`);
        side.classList.remove("is-fixed", "is-bottom");
        side.style.position = "fixed";
        side.style.top = `${interpolatedTop}px`;
        side.style.bottom = "auto";
        side.style.left = "auto";
        side.style.right = `${sideRight}px`;
        side.style.width = `${currentSideRect.width}px`;
        side.style.zIndex = "7";
        return;
      }

      if (enterProgress < handoffEnd) {
        side.classList.remove("is-fixed", "is-bottom");
        side.style.position = "";
        side.style.bottom = "";
        side.style.top = "";
        side.style.left = "";
        side.style.right = "";
        side.style.width = "";
        side.style.zIndex = "";
        panel.style.setProperty("--player-side-right", `${sideRight}px`);
        panel.style.setProperty(`--${sideVarPrefix}-side-width`, `${currentSideRect.width}px`);
        return;
      }

      const panelRect = panel.getBoundingClientRect();
      const sideRect = currentSideRect;
      const stickyBuffer = 24;
      const hasUpcomingPanel = Boolean(nextPanel);
      const shouldFix = hasUpcomingPanel
        ? panelRect.top <= -stickyBuffer
        : panelRect.top <= -stickyBuffer && panelRect.bottom > window.innerHeight + stickyBuffer;
      const shouldBottom = !hasUpcomingPanel && panelRect.bottom <= window.innerHeight + stickyBuffer;

      panel.style.setProperty("--player-side-right", `${sideRight}px`);
      panel.style.setProperty(`--${sideVarPrefix}-side-width`, `${sideRect.width}px`);

      side.style.position = "";
      side.style.bottom = "";
      side.style.top = "";
      side.style.left = "";
      side.style.right = "";
      side.style.width = "";
      side.style.zIndex = "";

      if (shouldFix) {
        side.classList.add("is-fixed");
        side.classList.remove("is-bottom");
        return;
      }

      if (shouldBottom) {
        side.classList.remove("is-fixed");
        side.classList.add("is-bottom");
        return;
      }

      side.classList.remove("is-fixed", "is-bottom");
    }

    function updateRomarioPortraitPosition() {
      updatePlayerPortraitPosition(romarioPanel, romarioSide, romarioPortraitWrap, "maradona", rivaldoPanel);
    }

    function updateRivaldoPortraitPosition() {
      updatePlayerPortraitPosition(rivaldoPanel, rivaldoSide, rivaldoPortraitWrap, "maradona", ronaldinhoPanel);
    }

    function updateRonaldinhoPortraitPosition() {
      updatePlayerPortraitPosition(ronaldinhoPanel, ronaldinhoSide, ronaldinhoPortraitWrap, "maradona", messiPanel);
    }

    function updateMessiPortraitPosition() {
      updatePlayerPortraitPosition(messiPanel, messiSide, messiPortraitWrap, "maradona", yamalPanel);
    }

    function updateYamalPortraitPosition() {
      updatePlayerPortraitPosition(
        yamalPanel,
        yamalSide,
        yamalPortraitWrap,
        "maradona",
        contributionSection
      );

      if (!yamalPanel || !yamalSide || !contributionSection || window.innerWidth <= 768) {
        if (yamalSide) {
          yamalSide.style.visibility = "visible";
        }
        return;
      }

      const contributionRect = contributionSection.getBoundingClientRect();
      if (contributionRect.top > window.innerHeight * 0.98) {
        yamalSide.style.visibility = "visible";
        return;
      }

      const exitProgress = easeInOutCubic(
        clamp((window.innerHeight * 0.88 - contributionRect.top) / (window.innerHeight * 0.5), 0, 1)
      );
      const remainingVisibility = 1 - exitProgress;

      yamalPanel.style.setProperty("--player-side-progress", remainingVisibility.toFixed(3));
      yamalSide.style.visibility = remainingVisibility <= 0.01 ? "hidden" : "visible";
    }

    function updateHeroIntro() {
      const rect = heroSection.getBoundingClientRect();
      const travelRange = Math.max(window.innerHeight * 0.9, 1);
      const progress = clamp(-rect.top / travelRange, 0, 1);
      const crestStopAt = 0.62;
      const crestProgress = clamp(progress / crestStopAt, 0, 1);
      const crestLocked = progress >= crestStopAt;
      const heroBottom = rect.bottom;
      const mottoProgress = clamp((-rect.top - window.innerHeight * 0.12) / (window.innerHeight * 0.38), 0, 1);

      heroCrest.style.opacity = heroBottom > 0 ? "1" : "0";
      heroMotto.style.opacity = heroBottom > 0 ? `${mottoProgress}` : "0";
      heroCrest.classList.toggle("is-locked", crestLocked);

      if (window.innerWidth <= 768) {
        heroCrest.style.position = heroBottom > 0 ? "fixed" : "absolute";
        heroCrest.style.left = "50%";
        if (crestLocked) {
          heroCrest.style.top = "50%";
          heroCrest.style.width = "min(30vw, 220px)";
          heroCrest.style.transform = "translate(-50%, -50%) scale(0.94)";
        } else {
          heroCrest.style.top = `${28 + crestProgress * 22}%`;
          heroCrest.style.width = `min(${40 - crestProgress * 10}vw, ${260 - crestProgress * 40}px)`;
          heroCrest.style.transform = `translate(-50%, -50%) scale(${1 - crestProgress * 0.06})`;
        }
        heroMotto.style.transform = `translateX(-50%) translateY(${24 - mottoProgress * 24}px)`;
        return;
      }

      heroCrest.style.position = heroBottom > 0 ? "fixed" : "absolute";
      if (crestLocked) {
        heroCrest.style.left = "33%";
        heroCrest.style.top = "50%";
        heroCrest.style.transform = "translate(-50%, -50%) scale(0.84)";
      } else {
        const left = 75 - crestProgress * 42;
        const scale = 1 - crestProgress * 0.16;
        heroCrest.style.left = `${left}%`;
        heroCrest.style.top = "50%";
        heroCrest.style.transform = `translate(-50%, -50%) scale(${scale})`;
      }
      heroMotto.style.transform = `translateX(-50%) translateY(${34 - mottoProgress * 34}px)`;
    }

    function updatePageProgress() {
      const scrollTop = window.scrollY;
      const maxScroll = Math.max(document.documentElement.scrollHeight - window.innerHeight, 1);
      const progress = clamp(scrollTop / maxScroll, 0, 1);
      progressFill.style.width = `${progress * 100}%`;
    }

    function updateKitPreviewPosition() {
      if (!kitArchivePanel || !kitPreviewColumn || !kitPreviewSticky || !kitTimelineRail) return;

      if (window.innerWidth <= 768) {
        kitPreviewSticky.classList.remove("is-floating", "is-bottom");
        kitTimelineRail.classList.remove("is-floating", "is-bottom");
        kitPreviewColumn.style.removeProperty("--kit-preview-left");
        kitPreviewColumn.style.removeProperty("--kit-preview-width");
        kitTimelineRail.style.removeProperty("--kit-timeline-left");
        kitTimelineRail.style.removeProperty("--kit-timeline-width");
        kitArchivePanel.style.setProperty("--archive-exit-progress", "0");
        updateKitTimelineTransform();
        return;
      }

      const panelRect = kitArchivePanel.getBoundingClientRect();
      const columnRect = kitPreviewColumn.getBoundingClientRect();
      const timelineParent = kitTimelineRail.parentElement;
      const timelineRect = timelineParent.getBoundingClientRect();
      const timelineParentStyle = window.getComputedStyle(timelineParent);
      const timelineWidth =
        timelineRect.width -
        parseFloat(timelineParentStyle.paddingLeft || "0") -
        parseFloat(timelineParentStyle.paddingRight || "0");
      const stickyHeight = kitPreviewSticky.offsetHeight;
      const railHeight = kitTimelineRail.offsetHeight || window.innerHeight * 0.72;
      const previewTop = window.innerHeight * 0.115;
      const railTop = window.innerHeight * 0.09;
      const currentPreviewRect = kitPreviewSticky.getBoundingClientRect();
      const currentRailRect = kitTimelineRail.getBoundingClientRect();
      const previewReady = currentPreviewRect.top <= previewTop + 1;
      const railReady = currentRailRect.top <= railTop + 1;
      const sectionReady = panelRect.top <= 0;
      const startFloating = sectionReady && previewReady && railReady;
      const stopThreshold = Math.max(previewTop + stickyHeight, railTop + railHeight) + 56;
      const stopFloating = panelRect.bottom <= stopThreshold;
      const fadeDistance = window.innerHeight * 0.32;
      const exitProgress = clamp((stopThreshold + fadeDistance - panelRect.bottom) / fadeDistance, 0, 1);

      kitPreviewColumn.style.setProperty("--kit-preview-left", `${columnRect.left}px`);
      kitPreviewColumn.style.setProperty("--kit-preview-width", `${columnRect.width}px`);
      kitTimelineRail.style.setProperty("--kit-timeline-left", `${timelineRect.left}px`);
      kitTimelineRail.style.setProperty("--kit-timeline-width", `${timelineWidth}px`);
      kitArchivePanel.style.setProperty("--archive-exit-progress", exitProgress.toFixed(3));

      if (!startFloating) {
        kitArchiveActivated = false;
        kitActivationScrollY = null;
        setActiveKit(0);
        kitPreviewSticky.classList.remove("is-floating", "is-bottom");
        kitTimelineRail.classList.remove("is-floating", "is-bottom");
        kitArchivePanel.style.setProperty("--archive-exit-progress", "0");
        updateKitTimelineTransform();
        return;
      }

      if (stopFloating) {
        if (!kitArchiveActivated) {
          kitActivationScrollY = window.scrollY;
        }
        kitArchiveActivated = true;
        kitPreviewSticky.classList.remove("is-floating");
        kitPreviewSticky.classList.add("is-bottom");
        kitTimelineRail.classList.remove("is-floating");
        kitTimelineRail.classList.add("is-bottom");
        updateKitTimelineTransform();
        return;
      }

      if (!kitArchiveActivated) {
        kitActivationScrollY = window.scrollY;
      }
      kitArchiveActivated = true;
      kitPreviewSticky.classList.remove("is-bottom");
      kitPreviewSticky.classList.add("is-floating");
      kitTimelineRail.classList.remove("is-bottom");
      kitTimelineRail.classList.add("is-floating");
      updateKitTimelineTransform();
    }

    function updateCrestPreviewPosition() {
      if (!crestPanel || !crestPreviewColumn || !crestPreviewSticky || !crestTimelineRail) return;

      if (window.innerWidth <= 768) {
        crestPanel.style.setProperty("--crest-enter-progress", "1");
        crestPreviewSticky.classList.remove("is-floating", "is-bottom");
        crestTimelineRail.classList.remove("is-floating", "is-bottom");
        crestPreviewColumn.style.removeProperty("--crest-preview-left");
        crestPreviewColumn.style.removeProperty("--crest-preview-width");
        crestTimelineRail.style.removeProperty("--crest-timeline-left");
        crestTimelineRail.style.removeProperty("--crest-timeline-width");
        updateCrestTimelineTransform();
        return;
      }

      const panelRect = crestPanel.getBoundingClientRect();
      const columnRect = crestPreviewColumn.getBoundingClientRect();
      const timelineRect = crestTimelineRail.parentElement.getBoundingClientRect();
      const stickyHeight = crestPreviewSticky.offsetHeight || window.innerHeight * 0.28;
      const railHeight = crestTimelineRail.offsetHeight || 224;
      const previewTop = window.innerHeight * 0.08;
      const railCenterY = window.innerHeight * 0.5 + 128;
      const railTop = railCenterY - railHeight / 2;
      const sectionReady = panelRect.top <= 0;
      const stopThreshold = Math.max(previewTop + stickyHeight, railTop + railHeight) + 72;
      const stopFloating = panelRect.bottom <= stopThreshold;
      const enterProgress = clamp((-panelRect.top) / (window.innerHeight * 0.24), 0, 1);

      crestPanel.style.setProperty("--crest-enter-progress", enterProgress.toFixed(3));

      crestPreviewColumn.style.setProperty("--crest-preview-left", `${columnRect.left}px`);
      crestPreviewColumn.style.setProperty("--crest-preview-width", `${Math.min(columnRect.width, 704)}px`);
      crestTimelineRail.style.setProperty("--crest-timeline-left", `${timelineRect.left}px`);
      crestTimelineRail.style.setProperty("--crest-timeline-width", `${timelineRect.width}px`);

      if (!sectionReady) {
        crestArchiveActivated = false;
        crestActivationScrollY = null;
        setActiveCrest(0);
        crestPreviewSticky.classList.remove("is-floating", "is-bottom");
        crestTimelineRail.classList.remove("is-floating", "is-bottom");
        updateCrestTimelineTransform();
        return;
      }

      if (stopFloating) {
        if (!crestArchiveActivated) {
          crestActivationScrollY = window.scrollY;
        }
        crestArchiveActivated = true;
        crestPreviewSticky.classList.remove("is-floating");
        crestPreviewSticky.classList.add("is-bottom");
        crestTimelineRail.classList.remove("is-floating");
        crestTimelineRail.classList.add("is-bottom");
        updateCrestTimelineTransform();
        return;
      }

      if (!crestArchiveActivated) {
        crestActivationScrollY = window.scrollY;
      }
      crestArchiveActivated = true;
      crestPreviewSticky.classList.remove("is-bottom");
      crestPreviewSticky.classList.add("is-floating");
      crestTimelineRail.classList.remove("is-bottom");
      crestTimelineRail.classList.add("is-floating");
      updateCrestTimelineTransform();
    }

    function updateLegacyTenTransition() {
      if (!legacyTenOrb || !legacyTenPanel || !crestPanel || !crestEraSteps.length || window.innerWidth <= 768) {
        if (legacyTenOrb) {
          legacyTenOrb.classList.remove("is-visible");
          legacyTenOrb.style.removeProperty("transform");
          legacyTenOrb.style.removeProperty("left");
          legacyTenOrb.style.removeProperty("top");
        }
        if (crestPanel) {
          crestPanel.classList.remove("is-handing-off");
          crestPanel.style.setProperty("--crest-fade-progress", "0");
        }
        legacyTenAnchor = null;
        return;
      }

      const { exitProgress } = updateLegacyTenExit();

      const finalIndex = crestEraSteps.length - 1;
      const finalStep = crestEraSteps[finalIndex];
      const finalDot = finalStep?.querySelector(".crest-era-dot");
      if (!finalDot) return;

      const crestRect = crestPanel.getBoundingClientRect();
      const legacyRect = legacyTenPanel.getBoundingClientRect();
      const fadeProgress = clamp((window.innerHeight * 1.02 - crestRect.bottom) / (window.innerHeight * 0.68), 0, 1);
      const handoffProgress = clamp((fadeProgress - 0.12) / 0.88, 0, 1);
      const settleProgress = clamp((window.innerHeight * 0.86 - legacyRect.top) / (window.innerHeight * 0.94), 0, 1);
      const moveProgress = easeInOutCubic(clamp(handoffProgress * 0.6 + settleProgress * 0.4, 0, 1));

      if (fadeProgress > 0.22 && activeCrestIndex !== finalIndex) {
        setActiveCrest(finalIndex);
      }

      crestPanel.style.setProperty("--crest-fade-progress", fadeProgress.toFixed(3));
      crestPanel.classList.toggle("is-handing-off", fadeProgress > 0.02);

      const dotRect = finalDot.getBoundingClientRect();
      const dotInView =
        dotRect.width > 0 &&
        dotRect.height > 0 &&
        dotRect.bottom > -window.innerHeight * 0.25 &&
        dotRect.top < window.innerHeight * 1.25;

      if ((dotInView && handoffProgress < 0.08) || !legacyTenAnchor) {
        legacyTenAnchor = {
          x: dotRect.left + dotRect.width / 2,
          y: dotRect.top + dotRect.height / 2
        };
      }

      if (!legacyTenAnchor) return;

      const startX = legacyTenAnchor.x;
      const startY = legacyTenAnchor.y;
      const targetX = window.innerWidth * 0.16;
      const orbFontSize = parseFloat(window.getComputedStyle(legacyTenOrb).fontSize) || 1;
      const dotFontSize = parseFloat(window.getComputedStyle(finalDot).fontSize) || orbFontSize;
      const startScale = clamp((dotFontSize / orbFontSize) * 0.94, 0.24, 0.5);
      const endScale = 4.42;
      const scale = startScale + (endScale - startScale) * moveProgress;
      const orbHeight = orbFontSize * endScale * 0.88;
      const rightColumnBottom = Math.max(
        legacyTenMain?.getBoundingClientRect().bottom || 0,
        legacyTenSide?.getBoundingClientRect().bottom || 0
      );
      const stopY = Math.min(window.innerHeight * 0.82, rightColumnBottom - orbHeight / 2);
      const targetY = Math.max(window.innerHeight * 0.62, stopY);
      const currentX = startX + (targetX - startX) * moveProgress;
      const currentY = startY + (targetY - startY) * moveProgress;
      const lockedX = exitProgress > 0.001 ? targetX : currentX;
      const lockedY = exitProgress > 0.001 ? targetY : currentY;
      const lockedScale = exitProgress > 0.001 ? endScale : scale;
      const opacity = clamp((0.18 + fadeProgress * 0.5 + moveProgress * 0.32) * (1 - exitProgress), 0, 1);
      const visible =
        fadeProgress > 0.04 &&
        legacyRect.top < window.innerHeight * 1.35 &&
        crestRect.bottom > -window.innerHeight * 0.95 &&
        exitProgress < 0.995;

      legacyTenOrb.classList.toggle("is-visible", visible);
      legacyTenOrb.style.left = `${lockedX}px`;
      legacyTenOrb.style.top = `${lockedY}px`;
      legacyTenOrb.style.transform = `translate(-50%, -50%) scale(${lockedScale})`;
      legacyTenOrb.style.opacity = visible ? `${Math.min(opacity, 1)}` : "0";
    }

    initColorsOpening();
    buildKitArchive();
    buildCrestArchive();
    buildContributionRain();
    buildTrophyScatter();
    buildLeagueRankChart();
    syncCrestArchiveHeight();
    updateLegacyTenExit();
    updateMaradonaToRomarioTransition();
    updateRomarioToRivaldoTransition();
    updateRivaldoToRonaldinhoTransition();
    updateRonaldinhoToMessiTransition();
    updateMessiToYamalTransition();
    updateHeroIntro();
    updatePageProgress();
    updateKitPreviewPosition();
    updateCrestPreviewPosition();
    updateActiveCrestFromScroll();
    updateLeagueRankScroll();
    updateLegacyTenTransition();
    updateMaradonaPortraitPosition();
    updateMaradonaFadeLock();
    updateRomarioPortraitPosition();
    updateRomarioFadeLock();
    updateRivaldoPortraitPosition();
    updateRivaldoFadeLock();
    updateRonaldinhoPortraitPosition();
    updateRonaldinhoFadeLock();
    updateMessiPortraitPosition();
    updateMessiFadeLock();
    updateYamalPortraitPosition();
    window.addEventListener("scroll", () => {
      updateHeroIntro();
      updatePageProgress();
      updateKitPreviewPosition();
      updateActiveKitFromScroll();
      updateCrestPreviewPosition();
      updateActiveCrestFromScroll();
      updateLeagueRankScroll();
      updateLegacyTenTransition();
      updateMaradonaToRomarioTransition();
      updateRomarioToRivaldoTransition();
      updateRivaldoToRonaldinhoTransition();
      updateRonaldinhoToMessiTransition();
      updateMessiToYamalTransition();
      updateMaradonaPortraitPosition();
      updateMaradonaFadeLock();
      updateRomarioPortraitPosition();
      updateRomarioFadeLock();
      updateRivaldoPortraitPosition();
      updateRivaldoFadeLock();
      updateRonaldinhoPortraitPosition();
      updateRonaldinhoFadeLock();
      updateMessiPortraitPosition();
      updateMessiFadeLock();
      updateYamalPortraitPosition();
    }, { passive: true });
    window.addEventListener("resize", () => {
      syncKitArchiveHeight();
      syncCrestArchiveHeight();
      updateHeroIntro();
      updatePageProgress();
      updateKitPreviewPosition();
      updateActiveKitFromScroll();
      updateCrestPreviewPosition();
      updateActiveCrestFromScroll();
      updateLeagueRankScroll();
      updateLegacyTenTransition();
      updateMaradonaToRomarioTransition();
      updateRomarioToRivaldoTransition();
      updateRivaldoToRonaldinhoTransition();
      updateRonaldinhoToMessiTransition();
      updateMessiToYamalTransition();
      updateMaradonaPortraitPosition();
      updateMaradonaFadeLock();
      updateRomarioPortraitPosition();
      updateRomarioFadeLock();
      updateRivaldoPortraitPosition();
      updateRivaldoFadeLock();
      updateRonaldinhoPortraitPosition();
      updateRonaldinhoFadeLock();
      updateMessiPortraitPosition();
      updateMessiFadeLock();
      updateYamalPortraitPosition();
    });
  </script>
</body>
</html>
