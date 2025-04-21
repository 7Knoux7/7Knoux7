# ⚡ Commit-KnouxReadme.ps1 | بقوة knoux7 ✨

$repoPath = "K:\MyProjects\Knoux7"   # ← غيّره لمكان مشروعك
Set-Location $repoPath

# 🎨 تأثير مرئي
Write-Host "`n⏳ جاري تهيئة الكون..." -ForegroundColor Cyan
Start-Sleep -Milliseconds 500

# 🎵 نغمة البداية
[console]::beep(700,200)
Write-Host "💻 كنـوكـس بيحـط بصمته…" -ForegroundColor Yellow
Start-Sleep -Milliseconds 700

# 🔍 التأكد من وجود تغييرات
$gitStatus = git status --porcelain
if (-not $gitStatus) {
    Write-Host "🚫 لا يوجد تغييرات جديدة في المستودع. سكربت توقف." -ForegroundColor Red
    exit
}

# ✅ خطوات Git
git add README.md
git commit -m "🌟 Legendary README.md update: Knoux's full identity, projects, and vision" `
             -m @"
• Real name: صادق الجزار | Abu Dhabi, UAE
• Authored Books: الكتاب المبين، قمر بني هاشم، خوارزميات قلب بشري، كود الحياة، كتاب التابعين
• Studied Islamic texts: صحيح البخاري، السيرة النبوية، الشمائل، دلائل النبوة
• Power Projects: KnouxClipboardAI، KnouxShield، KnouxSD Launcher، Knoux7 GUI
• Skills: PowerShell, Cybersecurity, AI, Markdown Wizardry
• Knoux Signature + ASCII + Contact Info
"@
git push

# 🖼️ ختم ASCII
$ascii = @"
██╗  ██╗███╗   ██╗ ██████╗ ██╗   ██╗██╗  ██╗
██║ ██╔╝████╗  ██║██╔═══██╗██║   ██║╚██╗██╔╝
█████╔╝ ██╔██╗ ██║██║   ██║██║   ██║ ╚███╔╝ 
██╔═██╗ ██║╚██╗██║██║   ██║██║   ██║ ██╔██╗ 
██║  ██╗██║ ╚████║╚██████╔╝╚██████╔╝██╔╝ ██╗
╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝
"@
Write-Host "`n$ascii" -ForegroundColor Green

# 🔥 النهاية المجنونة
Start-Sleep -Milliseconds 400
Write-Host "✅ README.md تم دمجه بختم knoux الأسطوري!" -ForegroundColor Cyan
Start-Sleep -Milliseconds 300
Write-Host "🎶 ولدلي البهيم يا knoux 🐴💻" -ForegroundColor Magenta
[console]::beep(900, 300)
