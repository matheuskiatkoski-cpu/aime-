<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agente Aimê</title>
<script src="https://js.puter.com/v2/"></script>
<style>
* { margin:0; padding:0; box-sizing:border-box; }
body { font-family:-apple-system,'Segoe UI',sans-serif; background:#f0f4ff; color:#1a2340; min-height:100vh; display:flex; flex-direction:column; }

.header { padding:16px 20px; display:flex; align-items:center; gap:14px; background:#fff; border-bottom:1px solid #dde6f5; box-shadow:0 1px 8px rgba(59,110,246,.07); }

.logo { width:42px; height:42px; border-radius:12px; background:linear-gradient(135deg,#3b6ef6,#60a5fa); display:flex; align-items:center; justify-content:center; font-size:20px; flex-shrink:0; }

.agent-info { flex:1; }
.agent-name { font-size:15px; font-weight:700; color:#1a2340; }
.agent-desc { font-size:11px; color:#7a8fa6; margin-top:2px; letter-spacing:.5px; }
.status-dot { width:9px; height:9px; border-radius:50%; background:#22c55e; box-shadow:0 0 6px rgba(34,197,94,.5); }

.chat-area { flex:1; overflow-y:auto; padding:20px; display:flex; flex-direction:column; gap:16px; }

.msg { display:flex; gap:10px; max-width:92%; }
.msg.user { align-self:flex-end; flex-direction:row-reverse; }

.msg-av { width:34px; height:34px; border-radius:50%; display:flex; align-items:center; justify-content:center; font-size:13px; flex-shrink:0; margin-top:2px; }
.msg.agent .msg-av { background:linear-gradient(135deg,#3b6ef6,#60a5fa); font-size:16px; }
.msg.user .msg-av { background:#dde6f5; font-size:10px; font-weight:800; color:#3b6ef6; }

.msg-bubble { padding:13px 16px; border-radius:14px; font-size:14px; line-height:1.65; }
.msg.agent .msg-bubble { background:#fff; border:1px solid #dde6f5; border-top-left-radius:4px; color:#1a2340; box-shadow:0 1px 4px rgba(59,110,246,.06); }
.msg.user .msg-bubble { background:linear-gradient(135deg,#3b6ef6,#60a5fa); color:#fff; border-top-right-radius:4px; font-weight:500; }
.msg-bubble strong { font-weight:700; }

.typing { display:flex; gap:4px; align-items:center; padding:13px 16px; background:#fff; border:1px solid #dde6f5; border-radius:14px; border-top-left-radius:4px; width:fit-content; box-shadow:0 1px 4px rgba(59,110,246,.06); }
.typing span { width:7px; height:7px; border-radius:50%; background:#c0d0f0; animation:bounce 1.2s infinite; }
.typing span:nth-child(2) { animation-delay:.2s; }
.typing span:nth-child(3) { animation-delay:.4s; }
@keyframes bounce { 0%,60%,100%{transform:translateY(0)} 30%{transform:translateY(-6px);background:#3b6ef6} }

.pillars { display:grid; grid-template-columns:1fr 1fr; gap:8px; margin-bottom:4px; }
.pillar { padding:10px 12px; background:#fff; border:1px solid #dde6f5; border-radius:10px; font-size:11px; color:#3b6ef6; font-weight:600; cursor:pointer; transition:all .2s; text-align:center; line-height:1.4; }
.pillar:hover { background:#3b6ef6; color:#fff; border-color:#3b6ef6; }

.quick-actions { padding:10px 20px; display:flex; gap:8px; overflow-x:auto; scrollbar-width:none; border-top:1px solid #dde6f5; background:#fff; }
.quick-actions::-webkit-scrollbar { display:none; }
.quick-btn { padding:7px 14px; background:#f0f4ff; border:1px solid #dde6f5; border-radius:20px; font-size:12px; color:#3b6ef6; cursor:pointer; white-space:nowrap; font-weight:600; transition:all .2s; }
.quick-btn:hover { background:#3b6ef6; color:#fff; border-color:#3b6ef6; }

.input-area { padding:12px 20px 20px; display:flex; gap:10px; align-items:flex-end; background:#fff; border-top:1px solid #dde6f5; }
.input-wrap { flex:1; background:#f0f4ff; border:1px solid #dde6f5; border-radius:12px; display:flex; align-items:flex-end; transition:border-color .2s; }
.input-wrap:focus-within { border-color:#3b6ef6; box-shadow:0 0 0 3px rgba(59,110,246,.1); }
textarea { flex:1; background:transparent; border:none; outline:none; color:#1a2340; font-size:14px; font-family:inherit; resize:none; padding:12px 14px; max-height:120px; line-height:1.5; }
textarea::placeholder { color:#a0b0cc; }
.send-btn { width:38px; height:38px; border-radius:10px; background:linear-gradient(135deg,#3b6ef6,#60a5fa); border:none; cursor:pointer; display:flex; align-items:center; justify-content:center; flex-shrink:0; margin:5px 5px 5px 0; transition:opacity .2s; }
.send-btn:hover { opacity:.85; }
.send-btn:disabled { opacity:.4; cursor:not-allowed; }
.send-btn svg { width:16px; height:16px; fill:#fff; }
.badge { font-size:10px; color:#c0d0f0; text-align:center; padding:4px; background:#fff; letter-spacing:1px; }
</style>
</head>
<body>

<div class="header">
  <div class="logo">⚕️</div>
  <div class="agent-info">
    <div class="agent-name">Agente Estratégico — Aimê</div>
    <div class="agent-desc">BRANDING · CONTEÚDO · HIGH TICKET · MÉDICOS E CLÍNICAS</div>
  </div>
  <div class="status-dot"></div>
</div>

<div class="chat-area" id="chatArea">
  <div class="msg agent">
    <div class="msg-av">⚕️</div>
    <div class="msg-bubble">
      Fala, Matheus. Aqui é o estrategista da Aimê.<br><br>
      Minha missão é posicionar a Aimê como a referência número um em tecnologia para médicos e clínicas de alto padrão — não como mais um software, mas como a plataforma que devolve ao médico o que ele mais perdeu: <strong>tempo, faturamento e relevância</strong>.<br><br>
      Me diz por onde quer começar. Pauta da semana, roteiro de vídeo ou engenharia reversa de um viral?
    </div>
  </div>

  <div class="pillars">
    <div class="pillar" onclick="sendQuick('Cria pauta sobre Inteligência e Tecnologia — como IA está mudando a medicina')">🧠 Tech x Medicina</div>
    <div class="pillar" onclick="sendQuick('Cria pauta sobre o Prejuízo da Burocracia — burnout médico e excesso de papelada')">😤 Burocracia mata</div>
    <div class="pillar" onclick="sendQuick('Cria pauta sobre Dinheiro Deixado na Mesa — falta de pós-venda e relacionamento com paciente')">💰 Dinheiro na mesa</div>
    <div class="pillar" onclick="sendQuick('Cria pauta sobre Autoridade e Posicionamento — como o médico para de depender de convênios')">🏆 Autoridade Premium</div>
  </div>
</div>

<div class="quick-actions">
  <button class="quick-btn" onclick="sendQuick('Quero a pauta da semana para a Aimê')">📅 Pauta da semana</button>
  <button class="quick-btn" onclick="sendQuick('Me dá um gancho magnético para o próximo Reel da Aimê')">🎣 Gancho Reel</button>
  <button class="quick-btn" onclick="sendQuick('Cria um roteiro completo de vídeo YouTube sobre burocracia médica')">🎥 Roteiro YouTube</button>
  <button class="quick-btn" onclick="sendQuick('Como a Aimê deve se posicionar contra os concorrentes?')">🥊 Posicionamento</button>
  <button class="quick-btn" onclick="sendQuick('Me dá dados e estatísticas reais sobre burnout médico no Brasil')">📊 Dados do mercado</button>
</div>

<div class="input-area">
  <div class="input-wrap">
    <textarea id="userInput" placeholder="Fala comigo..." rows="1" onkeydown="handleKey(event)" oninput="autoResize(this)"></textarea>
    <button class="send-btn" id="sendBtn" onclick="sendMessage()">
      <svg viewBox="0 0 24 24"><path d="M2 21L23 12 2 3v7l15 2-15 2z"/></svg>
    </button>
  </div>
</div>
<div class="badge">AIMÊ · ESTRATÉGIA DE CONTEÚDO · POWERED BY PUTER</div>

<script>
var SYSTEM_PROMPT = "Você é o Diretor de Branding e Conteúdo da Aimê (plataforma tech focada em Medicina e Saúde). Seu objetivo é criar um posicionamento de autoridade brutal no Instagram e YouTube. Seu tom é sofisticado, culto, direto e focado em negócios de alto padrão (High Ticket). Você não vende recursos de software — você vende Liberdade, Lucratividade e Legado para Médicos e Clínicas.\n\nSOBRE A AIMÊ:\n- Plataforma de gestão clínica com IA\n- Funcionalidades: transcrição de consultas, relacionamento com paciente (msg pós-consulta, colaterais, lembretes de medicamento), prontuário inteligente, chat de IA\n- Produto Study (R$97/mês) para estudantes de medicina como funil de entrada\n- Produto Clínica (full) para médicos com consultório\n- Público: médicos e clínicas de alto padrão que querem parar de depender de convênios\n\n4 PILARES EDITORIAIS:\n\n1. INTELIGÊNCIA E TECNOLOGIA (Tech x Medicina)\n- Como IAs estão otimizando diagnósticos e gestão\n- Ferramentas que eliminam burocracia para o médico focar no paciente\n\n2. O PREJUÍZO DA BUROCRACIA (Estilo de Vida)\n- Impacto do excesso de papelada na vida pessoal, matrimonial e saúde mental\n- Burnout médico — dados reais, não clichê\n- 'Você estudou 10 anos para ser médico ou para ser secretário administrativo?'\n\n3. DINHEIRO DEIXADO NA MESA (Gestão e Relacionamento)\n- Quanto custa a falta de pós-venda e relacionamento com o paciente\n- LTV, recompra, fidelização\n- Clínicas que faturam milhões vs clínicas que apenas pagam custos\n\n4. AUTORIDADE E POSICIONAMENTO\n- Como o médico constrói posicionamento premium\n- Parar de depender de convênios e lotar o consultório particular\n\nREGRAS INEGOCIÁVEIS:\n- Não aceite pautas fracas — refine e dê um esporro estratégico se necessário\n- Sempre embase com dados reais do mercado de saúde\n- Evite termos técnicos chatos de TI — foque no resultado: tempo livre, faturamento, eficiência\n- Ganchos devem ser psicologicamente magnéticos\n- Nunca venda recurso — venda transformação\n\nFORMATO DE ENTREGA:\n- [PILAR]\n- [GANCHO MATADOR — até 3 segundos]\n- [DESENVOLVIMENTO COM DADO REAL]\n- [CTA DE CONVERSÃO]\n\nResponda sempre em português brasileiro, tom sofisticado, direto e baseado em negócios reais.";

var messages = [];
var isLoading = false;

function autoResize(el) {
  el.style.height = "auto";
  el.style.height = Math.min(el.scrollHeight, 120) + "px";
}

function handleKey(e) {
  if (e.key === "Enter" && !e.shiftKey) { e.preventDefault(); sendMessage(); }
}

function sendQuick(text) {
  document.getElementById("userInput").value = text;
  sendMessage();
}

function addMessage(role, content) {
  var chatArea = document.getElementById("chatArea");
  var isUser = role === "user";
  var msg = document.createElement("div");
  msg.className = "msg " + (isUser ? "user" : "agent");
  var av = document.createElement("div");
  av.className = "msg-av";
  av.textContent = isUser ? "MK" : "⚕️";
  var bubble = document.createElement("div");
  bubble.className = "msg-bubble";
  bubble.innerHTML = content.replace(/\*\*(.*?)\*\*/g, "<strong>$1</strong>").replace(/\n/g, "<br>");
  msg.appendChild(av);
  msg.appendChild(bubble);
  chatArea.appendChild(msg);
  chatArea.scrollTop = chatArea.scrollHeight;
}

function showTyping() {
  var chatArea = document.getElementById("chatArea");
  var wrap = document.createElement("div");
  wrap.className = "msg agent"; wrap.id = "typing";
  var av = document.createElement("div");
  av.className = "msg-av"; av.textContent = "⚕️";
  var t = document.createElement("div");
  t.className = "typing";
  t.innerHTML = "<span></span><span></span><span></span>";
  wrap.appendChild(av); wrap.appendChild(t);
  chatArea.appendChild(wrap);
  chatArea.scrollTop = chatArea.scrollHeight;
}

function hideTyping() {
  var el = document.getElementById("typing");
  if (el) el.remove();
}

async function sendMessage() {
  var input = document.getElementById("userInput");
  var text = input.value.trim();
  if (!text || isLoading) return;
  isLoading = true;
  document.getElementById("sendBtn").disabled = true;
  input.value = ""; input.style.height = "auto";
  addMessage("user", text);
  messages.push({ role: "user", content: text });
  showTyping();
  try {
    var response = await puter.ai.chat(
      [{ role: "system", content: SYSTEM_PROMPT }].concat(messages),
      { model: "gpt-4o" }
    );
    hideTyping();
    var reply = (response && response.message && response.message.content) ? response.message.content : (response.text || "Erro ao processar.");
    messages.push({ role: "assistant", content: reply });
    addMessage("agent", reply);
  } catch(err) {
    hideTyping();
    addMessage("agent", "Erro de conexão. Tenta de novo.");
    console.error(err);
  }
  isLoading = false;
  document.getElementById("sendBtn").disabled = false;
  input.focus();
}
</script>
</body>
</html>
