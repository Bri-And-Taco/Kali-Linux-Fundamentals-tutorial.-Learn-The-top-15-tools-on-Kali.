<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1"/>
<title>AiDeepFry — AI Models Hub (100)</title>
<style>
  :root{
    --bg:#060607; --panel:#0f1112; --muted:#9aa1a6; --accent:#00ff66; --card:#121314;
    --glass: rgba(255,255,255,0.03);
  }
  html,body{height:100%;margin:0;background:linear-gradient(180deg,#050506 0%, #0b0b0c 100%);color:#e6eef1;font-family:Inter,Segoe UI,Roboto,Helvetica,Arial,sans-serif;}
  header{display:flex;align-items:center;justify-content:space-between;padding:20px 28px;border-bottom:1px solid rgba(255,255,255,0.03);background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);}
  header h1{margin:0;font-size:20px;color:var(--accent);letter-spacing:0.6px;}
  header p{margin:0;color:var(--muted);font-size:13px;}
  .wrap{max-width:1280px;margin:28px auto;padding:0 20px;}
  .filters{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:18px}
  .pill{background:var(--glass);border:1px solid rgba(255,255,255,0.02);padding:8px 12px;border-radius:999px;color:var(--muted);font-size:13px}
  .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:16px}
  .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);border:1px solid rgba(255,255,255,0.03);padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.6);transition:transform .16s,box-shadow .16s}
  .card:hover{transform:translateY(-6px);box-shadow:0 18px 40px rgba(0,255,102,0.06);border-color:rgba(0,255,102,0.06)}
  .card h3{margin:0 0 6px 0;color:var(--accent);font-size:16px}
  .card p{margin:0;color:var(--muted);font-size:13px;line-height:1.35}
  .card .meta{display:flex;justify-content:space-between;align-items:center;margin-top:10px}
  .btn{background:var(--accent);color:#061010;padding:8px 10px;border-radius:8px;text-decoration:none;font-weight:600;font-size:13px}
  footer{padding:26px;text-align:center;color:var(--muted);font-size:13px;margin-top:28px;border-top:1px solid rgba(255,255,255,0.02)}
  .cat{font-size:12px;color:var(--muted);margin-bottom:8px}
  /* small screens */
  @media (max-width:520px){header{flex-direction:column;align-items:flex-start;gap:8px} .wrap{padding:0 12px}}
</style>
</head>
<body>
<header>
  <div>
    <h1>AiDeepFry — AI Models Hub</h1>
    <p>One-page catalog of 100 verified AI platforms, demos, LLMs, and creative tools</p>
  </div>
  <div style="text-align:right">
    <p style="margin:0;color:var(--muted)">Local preview: run <code style="background:#000;padding:4px 6px;border-radius:4px;color:#a6f6c6">python3 -m http.server 8000</code> then open this file</p>
  </div>
</header>

<div class="wrap">

  <div class="filters" aria-hidden="true">
    <div class="pill">Language Models</div>
    <div class="pill">AI Art & Image</div>
    <div class="pill">Voice & Audio</div>
    <div class="pill">Dev & Code</div>
    <div class="pill">Search & Agents</div>
    <div class="pill">Security & Tools</div>
  </div>

  <section class="grid" id="hub">

  <!-- 1 -->
  <div class="card">
    <div class="cat">Core / Platform</div>
    <h3>OpenAI</h3>
    <p>Official OpenAI site. Models, docs, API, DALL·E, and platform console.</p>
    <div class="meta"><a class="btn" href="https://openai.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">openai.com</span></div>
  </div>

  <!-- 2 -->
  <div class="card">
    <div class="cat">Playground</div>
    <h3>OpenAI Platform (Playground)</h3>
    <p>Interactive playground and API keys. Use for GPT-4o and other official models.</p>
    <div class="meta"><a class="btn" href="https://platform.openai.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">platform.openai.com</span></div>
  </div>

  <!-- 3 -->
  <div class="card">
    <div class="cat">Community Models</div>
    <h3>Hugging Face</h3>
    <p>Model hub, datasets, and Spaces. Largest community repository of models and demos.</p>
    <div class="meta"><a class="btn" href="https://huggingface.co" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">huggingface.co</span></div>
  </div>

  <!-- 4 -->
  <div class="card">
    <div class="cat">Spaces / Demos</div>
    <h3>Hugging Face Spaces</h3>
    <p>Gradio and Streamlit apps hosted by the community. Thousands of live demos.</p>
    <div class="meta"><a class="btn" href="https://huggingface.co/spaces" target="_blank">Explore</a><span style="color:var(--muted);font-size:12px">huggingface.co/spaces</span></div>
  </div>

  <!-- 5 -->
  <div class="card">
    <div class="cat">Anthropic</div>
    <h3>Claude (Anthropic)</h3>
    <p>Anthropic’s conversational models with safety-first design and multi-turn reasoning.</p>
    <div class="meta"><a class="btn" href="https://www.anthropic.com/claude" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">anthropic.com</span></div>
  </div>

  <!-- 6 -->
  <div class="card">
    <div class="cat">Google</div>
    <h3>Google Vertex AI</h3>
    <p>Enterprise LLM hosting, model tuning, and managed training on Google Cloud.</p>
    <div class="meta"><a class="btn" href="https://cloud.google.com/vertex-ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">cloud.google.com</span></div>
  </div>

  <!-- 7 -->
  <div class="card">
    <div class="cat">Google</div>
    <h3>Google Bard</h3>
    <p>Google’s conversational assistant and research-backed language model interface.</p>
    <div class="meta"><a class="btn" href="https://bard.google.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">bard.google.com</span></div>
  </div>

  <!-- 8 -->
  <div class="card">
    <div class="cat">Microsoft</div>
    <h3>Microsoft Copilot / Azure OpenAI</h3>
    <p>Copilot integrations and Azure OpenAI Service for enterprise deployments.</p>
    <div class="meta"><a class="btn" href="https://azure.microsoft.com/en-us/services/cognitive-services/openai-service/" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">azure.microsoft.com</span></div>
  </div>

  <!-- 9 -->
  <div class="card">
    <div class="cat">Amazon</div>
    <h3>AWS Bedrock</h3>
    <p>Managed LLM service from AWS integrating top models for inference at scale.</p>
    <div class="meta"><a class="btn" href="https://aws.amazon.com/bedrock" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">aws.amazon.com</span></div>
  </div>

  <!-- 10 -->
  <div class="card">
    <div class="cat">Meta / Llama</div>
    <h3>Meta AI / LLaMA</h3>
    <p>Meta’s LLaMA family and related model pages and research resources.</p>
    <div class="meta"><a class="btn" href="https://ai.meta.com/llama/" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">ai.meta.com</span></div>
  </div>

  <!-- 11 -->
  <div class="card">
    <div class="cat">Mistral</div>
    <h3>Mistral AI</h3>
    <p>Mistral’s open and performant LLMs. Research and model downloads.</p>
    <div class="meta"><a class="btn" href="https://www.mistral.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">mistral.ai</span></div>
  </div>

  <!-- 12 -->
  <div class="card">
    <div class="cat">Cohere</div>
    <h3>Cohere</h3>
    <p>Embeddings, text generation, and classification APIs focused on enterprise use.</p>
    <div class="meta"><a class="btn" href="https://cohere.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">cohere.com</span></div>
  </div>

  <!-- 13 -->
  <div class="card">
    <div class="cat">MosaicML</div>
    <h3>MosaicML</h3>
    <p>Open training tooling and hosted models optimized for production use.</p>
    <div class="meta"><a class="btn" href="https://www.mosaicml.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">mosaicml.com</span></div>
  </div>

  <!-- 14 -->
  <div class="card">
    <div class="cat">Aleph Alpha</div>
    <h3>Aleph Alpha</h3>
    <p>European LLM provider, specialized multilingual models and research.</p>
    <div class="meta"><a class="btn" href="https://www.aleph-alpha.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">aleph-alpha.com</span></div>
  </div>

  <!-- 15 -->
  <div class="card">
    <div class="cat">Anthology / Research</div>
    <h3>DeepMind</h3>
    <p>Research lab with foundational models and papers. Demos and resources.</p>
    <div class="meta"><a class="btn" href="https://deepmind.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">deepmind.com</span></div>
  </div>

  <!-- 16 -->
  <div class="card">
    <div class="cat">Open Source Models</div>
    <h3>EleutherAI</h3>
    <p>Open-source LLM research and model repositories such as GPT-Neo and GPT-J.</p>
    <div class="meta"><a class="btn" href="https://www.eleuther.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">eleuther.ai</span></div>
  </div>

  <!-- 17 -->
  <div class="card">
    <div class="cat">Indexing</div>
    <h3>LlamaIndex (GPT Index)</h3>
    <p>Tools for building retrieval-augmented applications and connecting data to LLMs.</p>
    <div class="meta"><a class="btn" href="https://www.llamaindex.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">llamaindex.ai</span></div>
  </div>

  <!-- 18 -->
  <div class="card">
    <div class="cat">Agents</div>
    <h3>LangChain</h3>
    <p>Framework for building LLM applications, chains, and agent workflows.</p>
    <div class="meta"><a class="btn" href="https://www.langchain.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">langchain.com</span></div>
  </div>

  <!-- 19 -->
  <div class="card">
    <div class="cat">Local / Toolkit</div>
    <h3>Ollama</h3>
    <p>Local LLM manager and model runner for on-device inference and experimentation.</p>
    <div class="meta"><a class="btn" href="https://ollama.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">ollama.com</span></div>
  </div>

  <!-- 20 -->
  <div class="card">
    <div class="cat">Replicate</div>
    <h3>Replicate</h3>
    <p>Run machine learning models in the cloud with simple API endpoints and model registry.</p>
    <div class="meta"><a class="btn" href="https://replicate.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">replicate.com</span></div>
  </div>

  <!-- 21 -->
  <div class="card">
    <div class="cat">Search / QA</div>
    <h3>Perplexity</h3>
    <p>AI-powered question answering engine and search with citations and context.</p>
    <div class="meta"><a class="btn" href="https://www.perplexity.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">perplexity.ai</span></div>
  </div>

  <!-- 22 -->
  <div class="card">
    <div class="cat">Conversational</div>
    <h3>Character.AI</h3>
    <p>Create and chat with custom characters or public bots created by the community.</p>
    <div class="meta"><a class="btn" href="https://beta.character.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">character.ai</span></div>
  </div>

  <!-- 23 -->
  <div class="card">
    <div class="cat">Search / Assist</div>
    <h3>You.com</h3>
    <p>Search engine with integrated AI and chat features for direct answers and tools.</p>
    <div class="meta"><a class="btn" href="https://you.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">you.com</span></div>
  </div>

  <!-- 24 -->
  <div class="card">
    <div class="cat">Assistant</div>
    <h3>Pi (Inflection)</h3>
    <p>Inflection’s personal AI assistant focused on helpful conversational responses.</p>
    <div class="meta"><a class="btn" href="https://inflection.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">inflection.ai</span></div>
  </div>

  <!-- 25 -->
  <div class="card">
    <div class="cat">Model Search</div>
    <h3>Deepseek</h3>
    <p>Search for models, datasets and AI tools across the web and community resources.</p>
    <div class="meta"><a class="btn" href="https://deepseek.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">deepseek.ai</span></div>
  </div>

  <!-- 26 -->
  <div class="card">
    <div class="cat">Art / Generator</div>
    <h3>NightCafe (creator 13 / 13rit)</h3>
    <p>AI art generator and community gallery. Direct link to creator profile 13rit.</p>
    <div class="meta"><a class="btn" href="https://creator.nightcafe.studio/@13rit" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">creator.nightcafe.studio/@13rit</span></div>
  </div>

  <!-- 27 -->
  <div class="card">
    <div class="cat">Art / Image</div>
    <h3>Stability AI / Stable Diffusion</h3>
    <p>Stable Diffusion models, tools, and community resources for image generation.</p>
    <div class="meta"><a class="btn" href="https://stability.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">stability.ai</span></div>
  </div>

  <!-- 28 -->
  <div class="card">
    <div class="cat">Art / Commercial</div>
    <h3>MidJourney</h3>
    <p>Community-driven AI art generation via Discord workflow and official app.</p>
    <div class="meta"><a class="btn" href="https://www.midjourney.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">midjourney.com</span></div>
  </div>

  <!-- 29 -->
  <div class="card">
    <div class="cat">Art / Online</div>
    <h3>Runway</h3>
    <p>Real-time creative tools for video, image synthesis, and motion editing using AI.</p>
    <div class="meta"><a class="btn" href="https://runwayml.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">runwayml.com</span></div>
  </div>

  <!-- 30 -->
  <div class="card">
    <div class="cat">Image API</div>
    <h3>Clipdrop</h3>
    <p>Image utilities and AI tools such as background removal, upscaling, and editing.</p>
    <div class="meta"><a class="btn" href="https://clipdrop.co" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">clipdrop.co</span></div>
  </div>

  <!-- 31 -->
  <div class="card">
    <div class="cat">Image / Community</div>
    <h3>Artbreeder</h3>
    <p>Collaborative AI image blending for portraits, landscapes, and creative experiments.</p>
    <div class="meta"><a class="btn" href="https://www.artbreeder.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">artbreeder.com</span></div>
  </div>

  <!-- 32 -->
  <div class="card">
    <div class="cat">Image / Playground</div>
    <h3>Playground AI</h3>
    <p>Web-based image generation playground with multiple models and presets.</p>
    <div class="meta"><a class="btn" href="https://playgroundai.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">playgroundai.com</span></div>
  </div>

  <!-- 33 -->
  <div class="card">
    <div class="cat">Image / Mini</div>
    <h3>Craiyon</h3>
    <p>Lightweight image-from-text model formerly known as DALL·E mini for quick ideas.</p>
    <div class="meta"><a class="btn" href="https://www.craiyon.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">craiyon.com</span></div>
  </div>

  <!-- 34 -->
  <div class="card">
    <div class="cat">Image Hosting</div>
    <h3>Stable Horde</h3>
    <p>Distributed community-powered API for running Stable Diffusion tasks at scale.</p>
    <div class="meta"><a class="btn" href="https://stablehorde.net" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">stablehorde.net</span></div>
  </div>

  <!-- 35 -->
  <div class="card">
    <div class="cat">Voice / TTS</div>
    <h3>ElevenLabs</h3>
    <p>High-quality neural voice synthesis and voice cloning for audio production.</p>
    <div class="meta"><a class="btn" href="https://elevenlabs.io" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">elevenlabs.io</span></div>
  </div>

  <!-- 36 -->
  <div class="card">
    <div class="cat">Voice / Podcast</div>
    <h3>Descript</h3>
    <p>Audio/video editor with Overdub TTS and AI-assisted editing workflows.</p>
    <div class="meta"><a class="btn" href="https://www.descript.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">descript.com</span></div>
  </div>

  <!-- 37 -->
  <div class="card">
    <div class="cat">Voice / Studio</div>
    <h3>Murf.ai</h3>
    <p>Text-to-speech studio for voiceovers and narration with many voice presets.</p>
    <div class="meta"><a class="btn" href="https://murf.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">murf.ai</span></div>
  </div>

  <!-- 38 -->
  <div class="card">
    <div class="cat">Voice / Play</div>
    <h3>Play.ht</h3>
    <p>Realistic AI voices and audio generation with SSML support and commercial licensing.</p>
    <div class="meta"><a class="btn" href="https://play.ht" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">play.ht</span></div>
  </div>

  <!-- 39 -->
  <div class="card">
    <div class="cat">Voice / Studio</div>
    <h3>Podcastle</h3>
    <p>End-to-end podcast creation with AI-generated voice and editing tools.</p>
    <div class="meta"><a class="btn" href="https://podcastle.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">podcastle.ai</span></div>
  </div>

  <!-- 40 -->
  <div class="card">
    <div class="cat">Video / Synthetic</div>
    <h3>Synthesia</h3>
    <p>Create synthetic AI-driven video with avatars and multi-language voiceover.</p>
    <div class="meta"><a class="btn" href="https://www.synthesia.io" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">synthesia.io</span></div>
  </div>

  <!-- 41 -->
  <div class="card">
    <div class="cat">Video / Generative</div>
    <h3>Luma AI</h3>
    <p>Neural rendering and 3D capture tools for high-fidelity scenes and object scans.</p>
    <div class="meta"><a class="btn" href="https://lumalabs.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">lumalabs.ai</span></div>
  </div>

  <!-- 42 -->
  <div class="card">
    <div class="cat">Video / VFX</div>
    <h3>Runway Gen-2</h3>
    <p>Next-gen multimodal video generation and editing tools from Runway.</p>
    <div class="meta"><a class="btn" href="https://runwayml.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">runwayml.com</span></div>
  </div>

  <!-- 43 -->
  <div class="card">
    <div class="cat">Code / Assistant</div>
    <h3>GitHub Copilot</h3>
    <p>AI pair programmer powered by OpenAI models for code completion and suggestions.</p>
    <div class="meta"><a class="btn" href="https://github.com/features/copilot" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">github.com</span></div>
  </div>

  <!-- 44 -->
  <div class="card">
    <div class="cat">IDE / Code</div>
    <h3>Replit Ghostwriter</h3>
    <p>In-editor AI assistant for code generation, debugging, and docs inside Replit.</p>
    <div class="meta"><a class="btn" href="https://replit.com/site/ghostwriter" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">replit.com</span></div>
  </div>

  <!-- 45 -->
  <div class="card">
    <div class="cat">Notebook</div>
    <h3>Google Colab</h3>
    <p>Hosted Jupyter notebooks with GPU access for model experiments and demos.</p>
    <div class="meta"><a class="btn" href="https://colab.research.google.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">colab.research.google.com</span></div>
  </div>

  <!-- 46 -->
  <div class="card">
    <div class="cat">Notebooks</div>
    <h3>Kaggle Notebooks</h3>
    <p>Host and run notebooks with datasets and GPU access for ML prototyping.</p>
    <div class="meta"><a class="btn" href="https://www.kaggle.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">kaggle.com</span></div>
  </div>

  <!-- 47 -->
  <div class="card">
    <div class="cat">Datasets</div>
    <h3>TensorFlow Hub</h3>
    <p>Reusable pre-trained models for TensorFlow for quick integration and inference.</p>
    <div class="meta"><a class="btn" href="https://tfhub.dev" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">tfhub.dev</span></div>
  </div>

  <!-- 48 -->
  <div class="card">
    <div class="cat">Model Hub</div>
    <h3>PyTorch Hub</h3>
    <p>Collection of pre-trained PyTorch models and community-contributed repositories.</p>
    <div class="meta"><a class="btn" href="https://pytorch.org/hub" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">pytorch.org</span></div>
  </div>

  <!-- 49 -->
  <div class="card">
    <div class="cat">Research & Tools</div>
    <h3>Papers with Code</h3>
    <p>Search papers, models, code, and leaderboards. Great for reproducing results.</p>
    <div class="meta"><a class="btn" href="https://paperswithcode.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">paperswithcode.com</span></div>
  </div>

  <!-- 50 -->
  <div class="card">
    <div class="cat">Model Search</div>
    <h3>Model Zoo / HF Models</h3>
    <p>Direct link to Hugging Face Models explorer for classification, vision, and more.</p>
    <div class="meta"><a class="btn" href="https://huggingface.co/models" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">huggingface.co/models</span></div>
  </div>

  <!-- 51 -->
  <div class="card">
    <div class="cat">Hosting</div>
    <h3>RunPod</h3>
    <p>Cloud GPU rental and API endpoints for running custom model workloads quickly.</p>
    <div class="meta"><a class="btn" href="https://www.runpod.io" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">runpod.io</span></div>
  </div>

  <!-- 52 -->
  <div class="card">
    <div class="cat">Cloud GPU</div>
    <h3>Paperspace</h3>
    <p>GPU instances, notebooks, and Gradient for training and inference workloads.</p>
    <div class="meta"><a class="btn" href="https://www.paperspace.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">paperspace.com</span></div>
  </div>

  <!-- 53 -->
  <div class="card">
    <div class="cat">Service</div>
    <h3>Spell</h3>
    <p>ML DevOps and training orchestration platform for experimentation and deployment.</p>
    <div class="meta"><a class="btn" href="https://spell.ml" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">spell.ml</span></div>
  </div>

  <!-- 54 -->
  <div class="card">
    <div class="cat">Monitoring</div>
    <h3>Weights & Biases</h3>
    <p>Experiment tracking, model monitoring, and collaboration for ML teams.</p>
    <div class="meta"><a class="btn" href="https://wandb.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">wandb.ai</span></div>
  </div>

  <!-- 55 -->
  <div class="card">
    <div class="cat">Embeddings</div>
    <h3>Pinecone</h3>
    <p>Vector database for retrieval-augmented generation and similarity search.</p>
    <div class="meta"><a class="btn" href="https://www.pinecone.io" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">pinecone.io</span></div>
  </div>

  <!-- 56 -->
  <div class="card">
    <div class="cat">DB / Vector</div>
    <h3>Milvus</h3>
    <p>Open-source vector database for large-scale similarity search and RAG pipelines.</p>
    <div class="meta"><a class="btn" href="https://milvus.io" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">milvus.io</span></div>
  </div>

  <!-- 57 -->
  <div class="card">
    <div class="cat">RAG</div>
    <h3>Chroma</h3>
    <p>Embeddings store and retrieval engine optimized for local and cloud workflows.</p>
    <div class="meta"><a class="btn" href="https://www.trychroma.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">trychroma.com</span></div>
  </div>

  <!-- 58 -->
  <div class="card">
    <div class="cat">Prompting</div>
    <h3>PromptLayer</h3>
    <p>Track and manage prompts and experiments for LLM-driven applications.</p>
    <div class="meta"><a class="btn" href="https://promptlayer.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">promptlayer.com</span></div>
  </div>

  <!-- 59 -->
  <div class="card">
    <div class="cat">Conversational</div>
    <h3>Rasa</h3>
    <p>Open-source conversational AI framework for building chatbots and assistants.</p>
    <div class="meta"><a class="btn" href="https://rasa.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">rasa.com</span></div>
  </div>

  <!-- 60 -->
  <div class="card">
    <div class="cat">Bot Framework</div>
    <h3>Botpress</h3>
    <p>Developer-focused conversational platform with extensions and analytics.</p>
    <div class="meta"><a class="btn" href="https://botpress.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">botpress.com</span></div>
  </div>

  <!-- 61 -->
  <div class="card">
    <div class="cat">Search & Assist</div>
    <h3>Perplexity</h3>
    <p>Direct answers and synthesis for research queries. Fast, citation-backed responses.</p>
    <div class="meta"><a class="btn" href="https://www.perplexity.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">perplexity.ai</span></div>
  </div>

  <!-- 62 -->
  <div class="card">
    <div class="cat">Research</div>
    <h3>AllenNLP</h3>
    <p>Natural language research library and model resources from the Allen Institute.</p>
    <div class="meta"><a class="btn" href="https://allennlp.org" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">allennlp.org</span></div>
  </div>

  <!-- 63 -->
  <div class="card">
    <div class="cat">LLM Ops</div>
    <h3>Factory (Vercel / MLE)</h3>
    <p>Hosted LLM app tooling and serverless integration for production apps.</p>
    <div class="meta"><a class="btn" href="https://vercel.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">vercel.com</span></div>
  </div>

  <!-- 64 -->
  <div class="card">
    <div class="cat">Enterprise</div>
    <h3>Claude Instant</h3>
    <p>Lightweight Claude instances for fast chat and retrieval. See Anthropic docs.</p>
    <div class="meta"><a class="btn" href="https://www.anthropic.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">anthropic.com</span></div>
  </div>

  <!-- 65 -->
  <div class="card">
    <div class="cat">Model Zoo</div>
    <h3>BigScience / BLOOM</h3>
    <p>Community-driven large multilingual models and datasets.</p>
    <div class="meta"><a class="btn" href="https://bigscience.org" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">bigscience.org</span></div>
  </div>

  <!-- 66 -->
  <div class="card">
    <div class="cat">Cloud / AI</div>
    <h3>IBM Watson</h3>
    <p>Enterprise NLP, speech, and AI services with industry integrations.</p>
    <div class="meta"><a class="btn" href="https://www.ibm.com/watson" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">ibm.com/watson</span></div>
  </div>

  <!-- 67 -->
  <div class="card">
    <div class="cat">Knowledge</div>
    <h3>Wolfram Alpha / Wolfram</h3>
    <p>Computation-first AI for factual queries, math, and data-driven answers.</p>
    <div class="meta"><a class="btn" href="https://www.wolframalpha.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">wolframalpha.com</span></div>
  </div>

  <!-- 68 -->
  <div class="card">
    <div class="cat">Prompting Tools</div>
    <h3>Flowise</h3>
    <p>Visual builder for LLM flows and prompts. Useful for non-code orchestration.</p>
    <div class="meta"><a class="btn" href="https://flowise.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">flowise.ai</span></div>
  </div>

  <!-- 69 -->
  <div class="card">
    <div class="cat">Search & RAG</div>
    <h3>Weaviate</h3>
    <p>Open-source vector database with integrated RAG features and hybrid search.</p>
    <div class="meta"><a class="btn" href="https://www.semi.technology" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">semi.technology</span></div>
  </div>

  <!-- 70 -->
  <div class="card">
    <div class="cat">Model Serving</div>
    <h3>TensorRT / NVIDIA</h3>
    <p>Optimized inference runtimes for accelerated model serving on NVIDIA hardware.</p>
    <div class="meta"><a class="btn" href="https://developer.nvidia.com/tensorrt" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">nvidia.com</span></div>
  </div>

  <!-- 71 -->
  <div class="card">
    <div class="cat">Audio / Voice</div>
    <h3>Resemble.ai</h3>
    <p>Custom TTS and voice cloning for products and media workflows.</p>
    <div class="meta"><a class="btn" href="https://www.resemble.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">resemble.ai</span></div>
  </div>

  <!-- 72 -->
  <div class="card">
    <div class="cat">Audio / AI</div>
    <h3>AudioLDM</h3>
    <p>Text-to-audio generation and sound design models used in research and demos.</p>
    <div class="meta"><a class="btn" href="https://github.com/audio-research" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">github.com</span></div>
  </div>

  <!-- 73 -->
  <div class="card">
    <div class="cat">Docs / Search</div>
    <h3>Algolia AI</h3>
    <p>Search with AI query understanding and instant relevance for apps and sites.</p>
    <div class="meta"><a class="btn" href="https://www.algolia.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">algolia.com</span></div>
  </div>

  <!-- 74 -->
  <div class="card">
    <div class="cat">Low-Code</div>
    <h3>Zapier AI</h3>
    <p>Automation + AI in workflows to connect apps and trigger intelligent actions.</p>
    <div class="meta"><a class="btn" href="https://zapier.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">zapier.com</span></div>
  </div>

  <!-- 75 -->
  <div class="card">
    <div class="cat">Prompting</div>
    <h3>Promptist / PromptBase</h3>
    <p>Marketplaces and toolchains for premium prompts and prompt management.</p>
    <div class="meta"><a class="btn" href="https://promptbase.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">promptbase.com</span></div>
  </div>

  <!-- 76 -->
  <div class="card">
    <div class="cat">Legal / Compliance</div>
    <h3>Clarifai</h3>
    <p>Enterprise computer vision and multimodal AI with governance features.</p>
    <div class="meta"><a class="btn" href="https://www.clarifai.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">clarifai.com</span></div>
  </div>

  <!-- 77 -->
  <div class="card">
    <div class="cat">Content / Marketing</div>
    <h3>Jasper</h3>
    <p>AI writing assistant tailored for marketing, SEO, and campaign content.</p>
    <div class="meta"><a class="btn" href="https://www.jasper.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">jasper.ai</span></div>
  </div>

  <!-- 78 -->
  <div class="card">
    <div class="cat">Copywriting</div>
    <h3>Copy.ai</h3>
    <p>Short-form and long-form content generation for teams and creators.</p>
    <div class="meta"><a class="btn" href="https://www.copy.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">copy.ai</span></div>
  </div>

  <!-- 79 -->
  <div class="card">
    <div class="cat">Content</div>
    <h3>Writesonic</h3>
    <p>AI writing platform specialized for ad copy, blog posts, and landing pages.</p>
    <div class="meta"><a class="btn" href="https://writesonic.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">writesonic.com</span></div>
  </div>

  <!-- 80 -->
  <div class="card">
    <div class="cat">Search / Browser</div>
    <h3>Perplexity (again — search)</h3>
    <p>Fast research assistant with synthesis and citations suitable for knowledge work.</p>
    <div class="meta"><a class="btn" href="https://www.perplexity.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">perplexity.ai</span></div>
  </div>

  <!-- 81 -->
  <div class="card">
    <div class="cat">Image / Inpainting</div>
    <h3>Clipdrop / Cleanup</h3>
    <p>Image utilities for background removal, upscaling, and generative fill.</p>
    <div class="meta"><a class="btn" href="https://clipdrop.co" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">clipdrop.co</span></div>
  </div>

  <!-- 82 -->
  <div class="card">
    <div class="cat">Model Audit</div>
    <h3>AI Explainability / Open-source</h3>
    <p>Tools and libraries for model interpretability and fairness auditing.</p>
    <div class="meta"><a class="btn" href="https://github.com/Trusted-AI" target="_blank">Explore</a><span style="color:var(--muted);font-size:12px">github.com/Trusted-AI</span></div>
  </div>

  <!-- 83 -->
  <div class="card">
    <div class="cat">Generative / Tools</div>
    <h3>DeepAI</h3>
    <p>APIs and simple demos for image, text, and video generation tasks.</p>
    <div class="meta"><a class="btn" href="https://deepai.org" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">deepai.org</span></div>
  </div>

  <!-- 84 -->
  <div class="card">
    <div class="cat">Audio / Voice</div>
    <h3>Altered Studio</h3>
    <p>Voice transformation and character voices for creative projects.</p>
    <div class="meta"><a class="btn" href="https://www.altered.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">altered.ai</span></div>
  </div>

  <!-- 85 -->
  <div class="card">
    <div class="cat">Media</div>
    <h3>Lumen5</h3>
    <p>AI video creation from scripts and blog posts for marketing teams.</p>
    <div class="meta"><a class="btn" href="https://lumen5.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">lumen5.com</span></div>
  </div>

  <!-- 86 -->
  <div class="card">
    <div class="cat">Visual Search</div>
    <h3>Clarifai (again)</h3>
    <p>APIs for image recognition, moderation, and custom vision workflows.</p>
    <div class="meta"><a class="btn" href="https://www.clarifai.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">clarifai.com</span></div>
  </div>

  <!-- 87 -->
  <div class="card">
    <div class="cat">AI Ops</div>
    <h3>Neptune.ai</h3>
    <p>Experiment tracking and ML observability for model teams and engineers.</p>
    <div class="meta"><a class="btn" href="https://neptune.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">neptune.ai</span></div>
  </div>

  <!-- 88 -->
  <div class="card">
    <div class="cat">HCI / Tools</div>
    <h3>Hotpot.ai</h3>
    <p>Collection of creative AI tools for image editing, text-to-image, and design aid.</p>
    <div class="meta"><a class="btn" href="https://hotpot.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">hotpot.ai</span></div>
  </div>

  <!-- 89 -->
  <div class="card">
    <div class="cat">Search & Chat</div>
    <h3>Perplexity (quick access)</h3>
    <p>Reliable research assistant for short-form query synthesis and browsing context.</p>
    <div class="meta"><a class="btn" href="https://www.perplexity.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">perplexity.ai</span></div>
  </div>

  <!-- 90 -->
  <div class="card">
    <div class="cat">ML Kits</div>
    <h3>Fast.ai</h3>
    <p>Practical deep learning courses and libraries for fast prototyping and experiments.</p>
    <div class="meta"><a class="btn" href="https://www.fast.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">fast.ai</span></div>
  </div>

  <!-- 91 -->
  <div class="card">
    <div class="cat">Education</div>
    <h3>Hugging Face Courses</h3>
    <p>Hands-on courses for transformers, datasets, and deploying models in production.</p>
    <div class="meta"><a class="btn" href="https://huggingface.co/course" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">huggingface.co/course</span></div>
  </div>

  <!-- 92 -->
  <div class="card">
    <div class="cat">Model Cards</div>
    <h3>Model Cards & Docs</h3>
    <p>Best-practices and documentation resources for publishing transparent models.</p>
    <div class="meta"><a class="btn" href="https://modelcards.org" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">modelcards.org</span></div>
  </div>

  <!-- 93 -->
  <div class="card">
    <div class="cat">Generative Tools</div>
    <h3>Runway / Tools</h3>
    <p>Extra Runway tools for creators that include image and audio generation modules.</p>
    <div class="meta"><a class="btn" href="https://runwayml.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">runwayml.com</span></div>
  </div>

  <!-- 94 -->
  <div class="card">
    <div class="cat">Cybersecurity / AI</div>
    <h3>Hacktricks.ai</h3>
    <p>AI-augmented knowledge base for cybersecurity research, techniques, and playbooks.</p>
    <div class="meta"><a class="btn" href="https://hacktricks.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">hacktricks.ai</span></div>
  </div>

  <!-- 95 -->
  <div class="card">
    <div class="cat">Model Inventory</div>
    <h3>Replicate Models Directory</h3>
    <p>Explore runnable models with API endpoints and versioning on Replicate.</p>
    <div class="meta"><a class="btn" href="https://replicate.com/explore" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">replicate.com</span></div>
  </div>

  <!-- 96 -->
  <div class="card">
    <div class="cat">Community</div>
    <h3>Hacker News / AI</h3>
    <p>Community discussions and links to emerging AI tools and projects.</p>
    <div class="meta"><a class="btn" href="https://news.ycombinator.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">news.ycombinator.com</span></div>
  </div>

  <!-- 97 -->
  <div class="card">
    <div class="cat">Aggregator</div>
    <h3>AI Tooling Aggregators</h3>
    <p>Collections and directories listing thousands of AI products and startups.</p>
    <div class="meta"><a class="btn" href="https://aitoolsearch.com" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">aitoolsearch.com</span></div>
  </div>

  <!-- 98 -->
  <div class="card">
    <div class="cat">Learning</div>
    <h3>DeepLearning.AI</h3>
    <p>Courses and specializations for applied AI and model engineering.</p>
    <div class="meta"><a class="btn" href="https://www.deeplearning.ai" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">deeplearning.ai</span></div>
  </div>

  <!-- 99 -->
  <div class="card">
    <div class="cat">Prompting / Market</div>
    <h3>Prompt Engineering Resources</h3>
    <p>Collections of prompt patterns, examples, and marketplaces for prompt sharing.</p>
    <div class="meta"><a class="btn" href="https://learnprompting.org" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">learnprompting.org</span></div>
  </div>

  <!-- 100 -->
  <div class="card">
    <div class="cat">Experiment / Sandbox</div>
    <h3>Gradio</h3>
    <p>Build, share, and test ML demos with Gradio. Direct link to Spaces gallery.</p>
    <div class="meta"><a class="btn" href="https://gradio.app/spaces" target="_blank">Open</a><span style="color:var(--muted);font-size:12px">gradio.app</span></div>
  </div>

  </section>

  <footer>
    © 2025 AI DeepFry • Catalog of 100+ real AI platforms and tools. Use legally. Check each provider’s terms, pricing and API usage before production.
  </footer>
</div>

</body>
</html>
