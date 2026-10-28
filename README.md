<div align="center">

  <!-- Анимированный баннер-шапка -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=21,24&height=180&section=header&text=Viktor_Dedka&fontSize=50&fontAlignY=35&animation=fadeIn&fontColor=ffffff&desc=Junior%20Systems%20Developer&descFontSize=20&descAlignY=60&descAlign=50" width="100%" />

  <table>
    <tr>
      <td width="40%" align="center">
        <!-- Твоя гифка с мишкой -->
        <img src="https://media.tenor.com/GN73MKBawZYAAAAi/busy-cute.gif" width="220px" />
      </td>
      <td width="60%">
        <h2>🦀 Low-level wizardry & zero-cost abstractions</h2>
        <p>Увлечён системным программированием, управлением памятью и созданием легковесного, быстрого софта.</p>
        <p>
          🎯 <b>Фокус:</b> Архитектура ОС, компиляторы и высокопроизводительные утилиты.<br/>
          🌱 <b>Изучаю:</b> Внутреннее устройство Linux, eBPF, параллельные вычисления.
        </p>
        <div>
          <img src="https://img.shields.io/badge/Primary-Rust-%23e43717?style=flat-square&logo=rust&logoColor=white" />
          <img src="https://img.shields.io/badge/Favorite-Zig-%23f7a41d?style=flat-square&logo=zig&logoColor=black" />
          <img src="https://img.shields.io/badge/OS-Linux-%23FCC624?style=flat-square&logo=linux&logoColor=black" />
        </div>
      </td>
    </tr>
  </table>

</div>

---

### ⚡ // ABOUT_ME.zig

```zig
const std = @import("std");

fn Github(nice_Developer: []const u8) void {
    if (std.mem.eql(u8, nice_Developer, "Viktor")) {
        std.debug.print("{s} Junior Systems Developer", .{nice_Developer});
    } else {
        std.debug.print("no people", .{});
    }
}

pub fn main() !void {
    Github("Viktor");
}

