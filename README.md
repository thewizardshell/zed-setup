<img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/ed8e5715-5316-4f0e-8e5a-ae388b1b3c18" />

# Zed Config


Uso LazyVim como editor principal, pero quería Zed para cuando necesito algo más rápido sin perder mis atajos. 

Encontré el [gist de oca159](https://gist.github.com/oca159) que ya tenía la base de lo que buscaba, lo tomé como punto de partida y ajusté algunas cosas para que matchee exacto con mi workflow.

## Setup

**Editor**: Zed con Vim mode  
**Font**: Cascadia Code NF  
**Theme**: Kanagawa Dragon  
**AI**: GPT-4.1 (Copilot)  
**Git**: LazyGit embebido  

## Organización

`space` como leader, igual que en LazyVim:

- `space f` - files
- `space g` - git  
- `space c` - code/LSP
- `space b` - buffers
- `space s` - search
- `space a` - AI
- `space w` - windows

Navegación entre paneles con `ctrl-h/j/k/l`, tabs con `space 1-9`, todo lo básico que esperas.

## Lo importante

- Vim motions + sneak
- LazyGit con `space g g`
- LSP funcionando
- Center on scroll automático
- AI integrado de Zed

## Créditos

Config base de [oca159](https://gist.github.com/oca159), modificada para mi uso.
