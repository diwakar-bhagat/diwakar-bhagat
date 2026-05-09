# Diwakar Bhagat
```aura width=860 height=260 link="https://github.com/diwakar-bhagat"
<div style={{
  width: '100%', height: '100%', background: '#050508',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 24,
  border: '1px solid rgba(110,80,220,0.3)'
}}>

  <style>{`
      @keyframes float-particle {
        0% { transform: translate(0, 0); opacity: 0; }
        50% { opacity: 0.8; }
        100% { transform: translate(120px, -60px); opacity: 0; }
      }
      @keyframes pulse-soft {
        0%, 100% { opacity: 0.4; transform: scale(1); }
        50% { opacity: 0.7; transform: scale(1.1); }
      }
      #bg-glow { animation: pulse-soft 12s ease-in-out infinite; }
    `}</style>

  {/* Background Effects */}
  <svg width="860" height="260" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="hgrad1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(102, 34, 238, 0.4)" />
        <stop offset="100%" stopColor="rgba(102, 34, 238, 0)" />
      </radialGradient>
    </defs>
    <circle id="bg-glow" cx="150" cy="130" r="200" fill="url(#hgrad1)" />
  </svg>

  <div style={{
    marginLeft: 60, width: 120, height: 120,
    borderRadius: 60, background: 'linear-gradient(135deg, #6622ee, #0088ff)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
    boxShadow: '0 0 40px rgba(102, 34, 238, 0.5)',
    border: '4px solid rgba(255,255,255,0.15)',
    zIndex: 2
  }}>
    <div style={{ fontSize: 64 }}>⚡</div>
  </div>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:40, gap:12, zIndex: 2 }}>
    <div style={{ 
      display:'flex', fontSize:54, fontWeight:900, color:'#ffffff', 
      letterSpacing:'-2px', lineHeight:1,
      textShadow: '0 10px 30px rgba(0,0,0,0.6)'
    }}>
      Diwakar Bhagat
    </div>
    <div style={{ display:'flex', fontSize:19, color:'rgba(255,255,255,0.7)', fontWeight:500, letterSpacing:'0.2px', maxWidth: 500 }}>
      Building AI/ML systems, workflow tooling, and infrastructure.
    </div>
    <div style={{ display:'flex', fontSize:14, color:'rgba(255,255,255,0.4)', fontStyle: 'italic' }}>
      "Trying to make complex systems feel less chaotic to operate."
    </div>
  </div>
</div>
```

## 🎯 Currently Interested In

- **Motion Representation Learning**: Exploring how machines understand and represent movement.
- **AI-Native ERP Systems**: Reimagining enterprise resource planning with intelligence at the core.
- **Distributed Automation**: Designing pipelines that coordinate complex tasks at scale.
- **Internal Tooling**: Reducing operational overhead through elegant automation.

---

## 💎 Selected Work

```aura width=860 height=300
<div style={{
  width: '100%', height: '100%', background: '#0a0a0f',
  display: 'flex', flexDirection: 'column', padding: 40,
  fontFamily: 'Inter', color: '#fff', borderRadius: 24,
  border: '1px solid rgba(255,255,255,0.08)',
  position: 'relative', overflow: 'hidden'
}}>
  <div style={{ display: 'flex', gap: 20 }}>
    {[
      { 
        title: 'Workflow Automation', 
        desc: 'Tooling for research & documentation to reduce repetitive manual coordination.', 
        icon: '🔧', color: '#6622ee' 
      },
      { 
        title: 'ERP Infrastructure', 
        desc: 'API-first systems focused on scalability and operational visibility.', 
        icon: '🏗️', color: '#0088ff' 
      },
      { 
        title: 'AI Internal Tools', 
        desc: 'Practical AI integrations for data handling and system orchestration.', 
        icon: '🧠', color: '#00ccbb' 
      }
    ].map((item, i) => (
      <div key={i} style={{
        flex: 1, padding: 28, background: 'linear-gradient(180deg, rgba(255,255,255,0.06) 0%, rgba(255,255,255,0.01) 100%)',
        borderRadius: 20, border: '1px solid rgba(255,255,255,0.12)',
        display: 'flex', flexDirection: 'column', gap: 16
      }}>
        <div style={{ 
          width: 52, height: 52, borderRadius: 14, 
          background: item.color + '22', 
          display: 'flex', alignItems: 'center', justifyContent: 'center',
          fontSize: 28, border: '1px solid ' + item.color + '44'
        }}>
          {item.icon}
        </div>
        <div style={{ fontSize: 22, fontWeight: 800, letterSpacing: '-0.5px' }}>{item.title}</div>
        <div style={{ fontSize: 14, color: '#999', lineHeight: 1.6 }}>{item.desc}</div>
      </div>
    ))}
  </div>
</div>
```

## 🛠️ Technical Focus

```aura width=860 height=140
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', justifyContent: 'space-around',
  fontFamily: 'Inter', borderRadius: 24, border: '1px solid rgba(255,255,255,0.06)'
}}>
  {[
    'Python', 'PyTorch', 'FastAPI', 'PostgreSQL', 'Redis', 'Docker'
  ].map((tech, i) => (
    <div key={i} style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', gap: 6 }}>
      <div style={{ 
        width: 12, height: 12, borderRadius: 6, 
        background: 'linear-gradient(135deg, #6622ee, #0088ff)',
        boxShadow: '0 0 10px rgba(102, 34, 238, 0.5)'
      }} />
      <div style={{ fontSize: 18, fontWeight: 900, color: '#fff', letterSpacing: '-0.5px' }}>{tech}</div>
    </div>
  ))}
</div>
```

---

## 🧭 Current Direction

Lately spending more time thinking about:
- **Workflow Orchestration**: How to manage complex dependencies with reliability.
- **Infrastructure Abstractions**: Making the underlying systems invisible to the user.
- **AI-Assisted Operations**: Automating the "boring" parts of system management.
- **System Reliability**: Ensuring stability under real-world usage and high coordination scale.

---

<div align="center">

## 🌐 Connect with Diwakar

```aura width=160 height=52 inline link="https://your-portfolio.com"
<div style={{
  width: '100%', height: '100%', background: '#111',
  display: 'flex', alignItems: 'center', justifyContent: 'center',
  borderRadius: 14, color: '#fff', fontSize: 16, fontWeight: 800,
  border: '1px solid rgba(255,255,255,0.12)', gap: 8
}}>
  <span>Portfolio</span>
</div>
```

```aura width=160 height=52 inline link="https://linkedin.com/in/diwakarbhagat"
<div style={{
  width: '100%', height: '100%', background: '#0077b5',
  display: 'flex', alignItems: 'center', justifyContent: 'center',
  borderRadius: 14, color: '#fff', fontSize: 16, fontWeight: 800,
  marginLeft: 14, gap: 8
}}>
  <span>LinkedIn</span>
</div>
```

```aura width=160 height=52 inline link="mailto:your-email@example.com"
<div style={{
  width: '100%', height: '100%', background: '#ff4466',
  display: 'flex', alignItems: 'center', justifyContent: 'center',
  borderRadius: 14, color: '#fff', fontSize: 16, fontWeight: 800,
  marginLeft: 14, gap: 8
}}>
  <span>Email</span>
</div>
```

<br/>
<br/>

```aura width=860 height=40 link="https://github.com/collectioneur/readme-aura"
  <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', width: '100%', height: '100%' }}>
    <div style={{ 
      display: 'flex', alignItems: 'center', gap: 8,
      padding: '6px 20px', borderRadius: 24, background: 'rgba(255,255,255,0.04)',
      border: '1px solid rgba(255,255,255,0.06)'
    }}>
      <span style={{ fontSize: 11, color: '#444', fontWeight: 900, letterSpacing: '1.2px' }}>
        POWERED BY README-AURA 0.4.5
      </span>
    </div>
  </div>
```

</div>
