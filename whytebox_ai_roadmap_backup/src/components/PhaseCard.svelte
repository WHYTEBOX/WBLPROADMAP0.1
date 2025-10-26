<script>
  export let phase;
  const geminiKey = import.meta.env.VITE_GEMINI_API_KEY;
  const openaiKey = import.meta.env.VITE_OPENAI_API_KEY;
</script>

<div class="phase-card">
  <h2>{phase}</h2>
  <p>AI-generated summary and narrative will appear here.</p>
</div>