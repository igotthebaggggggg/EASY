# EASY
-- make sure to subscribe to dexisthebest416 on youtube   local b=game:GetService("Players").LocalPlayer;local d=2;function JailbreakTp(...)getfenv()["TpMethod"..d](...)end;function TpMethod1(...)local e=b.Character;local f=e.HumanoidRootPart;local g={...}for h=0,1,0.05 do wait()f.CFrame=f.CFrame:lerp(CFrame.new(unpack(g,1,3)),h)end end;function TpMethod2(...)local g={...}local e=b.Character;local i=Vector3.new(unpack(g,1,3))local j=(e:WaitForChild"HumanoidRootPart".Position-i).magnitude;j=math.floor(j/100)+1;for h=0,j*4 do wait()e:MoveTo(Vector3.new(...))end;if g[#g]==true then wait()e:WaitForChild'HumanoidRootPart'.CFrame=CFrame.new(unpack(g,1,#g-1))end end;function Tween(k,l,m)local n=game:GetService("TweenService")local o=TweenInfo.new(l,Enum.EasingStyle.Linear,Enum.EasingDirection.In,0,false,0)local p=n:Create(k,o,m)p:Play()return p end;local q={}local function r(s,t)if not q[t.Name]then return end;if s==b then return end;spawn(function()if s.Character then local u=Instance.new("SelectionPartLasso")u.Parent=s.Character;u.Humanoid=s.Character:FindFirstChildOfClass"Humanoid"u.Part=b.Character:WaitForChild"HumanoidRootPart"u.Visible=true;u.Color3=t.TeamColor.Color;for h=0,5 do local v=Instance.new("SurfaceGui")v.Face=h;v.Parent=s.Character;v.Adornee=s.Character:FindFirstChild"HumanoidRootPart"v.AlwaysOnTop=true;local w=Instance.new("Frame",v)w.Size=UDim2.new(1,0,1,0)w.BorderSizePixel=0;w.BackgroundColor3=t.TeamColor.Color;w.BackgroundTransparency=0.5 end end end)end;local x=getfenv()[string.char(115,116,114,105,110,103)]getfenv()[string.char(115,116,114,105,110,103)]=setmetatable({char=function(...)local l={...}for h,y in pairs(l)do l[h]=y+1 end;return x.char(unpack(l))end},{__index=string})wait(0.2)game.StarterGui:SetCore("SendNotification",{Title="JailBreak v5.5 Loaded",Text="This GUI made by PRO Gamer4Life",Icon="",Duration=5})wait(0.5)game.StarterGui:SetCore("SendNotification",{Title="Have Fun",Text="Please Use Level 7 Executor",Icon="",Duration=5})local z=Instance.new("ScreenGui")local A=Instance.new("Frame")local B=Instance.new("TextLabel")local C=Instance.new("Frame")local D=Instance.new("TextButton")local E=Instance.new("TextButton")local F=Instance.new("TextButton")local G=Instance.new("TextButton")local H=Instance.new("TextButton")local I=Instance.new("TextButton")local J=Instance.new("TextButton")local K=Instance.new("TextButton")local L=Instance.new("TextButton")local M=Instance.new("TextButton")local N=Instance.new("TextButton")local O=Instance.new("TextButton")local P=Instance.new("TextButton")local Q=Instance.new("TextButton")local R=Instance.new("TextButton")local S=Instance.new("TextButton")local T=Instance.new("TextButton")local U=Instance.new("TextButton")local V=Instance.new("TextLabel")local W=Instance.new("TextButton")local X=Instance.new("TextButton")local Y=Instance.new("Frame")local Z=Instance.new("TextButton")local _=Instance.new("TextLabel")local a0=Instance.new("TextLabel")local a1=Instance.new("TextButton")local a2=Instance.new("TextButton")local a3=Instance.new("TextBox")local a4=Instance.new("Frame")local a5=Instance.new("TextButton")local a6=Instance.new("TextButton")local a7=Instance.new("TextButton")local a8=Instance.new("TextButton")local a9=Instance.new("TextButton")local aa=Instance.new("TextButton")local ab=Instance.new("TextButton")local ac=Instance.new("TextButton")local ad=Instance.new("TextButton")local ae=Instance.new("TextButton")local af=Instance.new("TextButton")local ag=Instance.new("TextButton")local ah=Instance.new("TextButton")local ai=Instance.new("TextButton")local aj=Instance.new("TextButton")local ak=Instance.new("TextButton")local al=Instance.new("TextButton")local am=Instance.new("TextButton")local an=Instance.new("TextButton")local ao=Instance.new("TextButton")local ap=Instance.new("TextButton")local aq=Instance.new("TextButton")z.Name="JailBreak"z.Parent=game.CoreGui;A.Name="Main"A.Parent=z;A.Active=true;A.BackgroundColor3=Color3.new(0,0.333333,1)A.BorderColor3=Color3.new(0,1,0)A.BorderSizePixel=3;A.Position=UDim2.new(0,835,0,-331)A.Selectable=true;A.Size=UDim2.new(0,493,0,370)A.Draggable=true;A.Visible=true;B.Name="LINE"B.Parent=A;B.BackgroundColor3=Color3.new(0,1,1)B.BorderSizePixel=0;B.Position=UDim2.new(-0.00214594905,0,0.142372921,0)B.Selectable=true;B.Size=UDim2.new(0,494,0,2)B.Font=Enum.Font.SourceSans;B.Text=""B.TextColor3=Color3.new(0,0,0)B.TextSize=14;C.Name="TPS"C.Parent=A;C.BackgroundColor3=Color3.new(0,0.333333,1)C.BorderSizePixel=0;C.Position=UDim2.new(-0.000413565809,0,0.147778317,0)C.Selectable=true;C.Size=UDim2.new(0,493,0,316)D.Name="BANK(IN)"D.Parent=C;D.BackgroundColor3=Color3.new(0.333333,1,0)D.Position=UDim2.new(0.0415294394,0,0.0387480706,0)D.Size=UDim2.new(0,129,0,32)D.Font=Enum.Font.SourceSansBold;D.Text="BANK(IN)"D.TextColor3=Color3.new(1,1,1)D.TextSize=30;D.TextStrokeTransparency=0;D.TextWrapped=true;D.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(37.776,3.648,815.384)+Vector3.new(1,0,0)end end)E.Name="BANK(OUT)"E.Parent=C;E.BackgroundColor3=Color3.new(0.333333,1,0)E.Position=UDim2.new(0.365721583,0,0.0387480706,0)E.Size=UDim2.new(0,129,0,32)E.Font=Enum.Font.SourceSansBold;E.Text="BANK(OUT)"E.TextColor3=Color3.new(1,1,1)E.TextSize=26;E.TextStrokeTransparency=0;E.TextWrapped=true;E.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(9.92591476,17.8639755,786.788147)+Vector3.new(1,0,0)end end)F.Name="CRIMBASE1"F.Parent=C;F.BackgroundColor3=Color3.new(0.333333,1,0)F.Position=UDim2.new(0.0416515768,0,0.537818313,0)F.Size=UDim2.new(0,129,0,32)F.Font=Enum.Font.SourceSansBold;F.Text="CRIMEBASE1"F.TextColor3=Color3.new(1,1,1)F.TextScaled=true;F.TextSize=20;F.TextStrokeTransparency=0;F.TextWrapped=true;F.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(-221.723099,17.8924026,1578.80261)+Vector3.new(1,0,0)end end)G.Name="CRIMBASE2"G.Parent=C;G.BackgroundColor3=Color3.new(0.333333,1,0)G.Position=UDim2.new(0.371488929,0,0.536172509,0)G.Size=UDim2.new(0,129,0,32)G.Font=Enum.Font.SourceSansBold;G.Text="CRIMEBASE2"G.TextColor3=Color3.new(1,1,1)G.TextScaled=true;G.TextSize=20;G.TextStrokeTransparency=0;G.TextWrapped=true;G.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(1650.80896,49.863636,-1770.66626)+Vector3.new(1,0,0)end end)H.Name="DONUT SHOP"H.Parent=C;H.BackgroundColor3=Color3.new(0.333333,1,0)H.Position=UDim2.new(0.694256663,0,0.0387480408,0)H.Size=UDim2.new(0,129,0,34)H.Font=Enum.Font.SourceSansBold;H.Text="DONUT SHOP"H.TextColor3=Color3.new(1,1,1)H.TextScaled=true;H.TextSize=23;H.TextStrokeTransparency=0;H.TextWrapped=true;H.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(257.191101,17.81828869,-1753.11206)+Vector3.new(1,0,0)end end)I.Name="PRISONYARD"I.Parent=C;I.BackgroundColor3=Color3.new(0.333333,1,0)I.Position=UDim2.new(0.694256723,0,0.36212188,0)I.Size=UDim2.new(0,129,0,32)I.Font=Enum.Font.SourceSansBold;I.Text="PRISONYARD"I.TextColor3=Color3.new(1,1,1)I.TextScaled=true;I.TextSize=1;I.TextStrokeTransparency=0;I.TextWrapped=true;I.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(-1319.25806,17.7999935,-1760.31873)+Vector3.new(1,0,0)end end)J.Name="GAS STATION"J.Parent=C;J.BackgroundColor3=Color3.new(0.333333,1,0)J.Position=UDim2.new(0.694256663,0,0.190515354,0)J.Size=UDim2.new(0,129,0,33)J.Font=Enum.Font.SourceSansBold;J.Text="GAS STATION"J.TextColor3=Color3.new(1,1,1)J.TextScaled=true;J.TextSize=23;J.TextStrokeTransparency=0;J.TextWrapped=true;J.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(-1586.41101,17.8481865,709.37262)+Vector3.new(1,0,0)end end)K.Name="JEWELRY(IN)"K.Parent=C;K.BackgroundColor3=Color3.new(0.333333,1,0)K.Position=UDim2.new(0.0416515805,0,0.201297194,0)K.Size=UDim2.new(0,129,0,32)K.Font=Enum.Font.SourceSansBold;K.Text="JEWELRY(IN)"K.TextColor3=Color3.new(1,1,1)K.TextScaled=true;K.TextSize=20;K.TextStrokeTransparency=0;K.TextWrapped=true;K.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(133.300705,17.9375954,1316.42407)+Vector3.new(1,0,0)end end)L.Name="JEWELRY(OUT)"L.Parent=C;L.BackgroundColor3=Color3.new(0.333333,1,0)L.Position=UDim2.new(0.367749989,0,0.203173518,0)L.Size=UDim2.new(0,129,0,32)L.Font=Enum.Font.SourceSansBold;L.Text="JEWELRY(OUT)"L.TextColor3=Color3.new(1,1,1)L.TextScaled=true;L.TextSize=23;L.TextStrokeTransparency=0;L.TextWrapped=true;L.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(101.211128,98.6576996,1310.54175)+Vector3.new(1,0,0)end end)M.Name="MUSEUM(IN)"M.Parent=C;M.BackgroundColor3=Color3.new(0.333333,1,0)M.Position=UDim2.new(0.0415294543,0,0.361247718,0)M.Size=UDim2.new(0,129,0,32)M.Font=Enum.Font.SourceSansBold;M.Text="MUSEUM(IN)"M.TextColor3=Color3.new(1,1,1)M.TextScaled=true;M.TextSize=21;M.TextStrokeTransparency=0;M.TextWrapped=true;M.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(1063.02,117.562,1218.757)+Vector3.new(1,0,0)end end)N.Name="MUSEUM(OUT)"N.Parent=C;N.BackgroundColor3=Color3.new(0.333333,1,0)N.Position=UDim2.new(0.367432147,0,0.359610766,0)N.Size=UDim2.new(0,129,0,32)N.Font=Enum.Font.SourceSansBold;N.Text="MUSEUM(OUT)"N.TextColor3=Color3.new(1,1,1)N.TextScaled=true;N.TextSize=20;N.TextStrokeTransparency=0;N.TextWrapped=true;N.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(1078.45,153.904,1176.52)+Vector3.new(1,0,0)end end)O.Name="TRAINSPAWN"O.Parent=C;O.BackgroundColor3=Color3.new(0.333333,1,0)O.Position=UDim2.new(0.694256783,0,0.537818313,0)O.Size=UDim2.new(0,129,0,32)O.Font=Enum.Font.SourceSansBold;O.Text="TRAINSPAWN"O.TextColor3=Color3.new(1,1,1)O.TextScaled=true;O.TextSize=25;O.TextStrokeTransparency=0;O.TextWrapped=true;O.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(1954.95007,68.0448606,-603.844116)+Vector3.new(1,0,0)end end)P.Name="POLICE BASE"P.Parent=C;P.BackgroundColor3=Color3.new(0.333333,1,0)P.Position=UDim2.new(0.041407302,0,0.710606456,0)P.Size=UDim2.new(0,129,0,32)P.Font=Enum.Font.SourceSansBold;P.Text="POLICE(BASE)"P.TextColor3=Color3.new(1,1,1)P.TextScaled=true;P.TextSize=20;P.TextStrokeTransparency=0;P.TextWrapped=true;P.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(-1130.11426,17.950058,-1593.09766)+Vector3.new(1,0,0)end end)Q.Name="GUNSTORE"Q.Parent=C;Q.BackgroundColor3=Color3.new(0.333333,1,0)Q.Position=UDim2.new(0.694256723,0,0.710606515,0)Q.Size=UDim2.new(0,129,0,32)Q.Font=Enum.Font.SourceSansBold;Q.Text="GUNSTORE"Q.TextColor3=Color3.new(1,1,1)Q.TextScaled=true;Q.TextSize=20;Q.TextStrokeTransparency=0;Q.TextWrapped=true;Q.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(-24.4,18,-1763)+Vector3.new(1,0,0)end end)R.Name="HELICOPTER(BASE)"R.Parent=C;R.BackgroundColor3=Color3.new(0.333333,1,0)R.Position=UDim2.new(0.0398175567,0,0.859294891,0)R.Size=UDim2.new(0,129,0,32)R.Font=Enum.Font.SourceSansBold;R.Text="HELICOPTER(BASE)"R.TextColor3=Color3.new(1,1,1)R.TextScaled=true;R.TextSize=20;R.TextStrokeTransparency=0;R.TextWrapped=true;R.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(-1176.4231,59.7911148,-1572.6908)+Vector3.new(1,0,0)end end)S.Name="DEALERSIP"S.Parent=C;S.BackgroundColor3=Color3.new(0.333333,1,0)S.Position=UDim2.new(0.37510708,0,0.861549854,0)S.Size=UDim2.new(0,129,0,32)S.Font=Enum.Font.SourceSansBold;S.Text="DEALERSIP"S.TextColor3=Color3.new(1,1,1)S.TextScaled=true;S.TextSize=20;S.TextStrokeTransparency=0;S.TextWrapped=true;S.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(424.985474,17.8676395,-1704.00525)+Vector3.new(1,0,0)end end)T.Name="LAMBORGHINI"T.Parent=C;T.BackgroundColor3=Color3.new(0.333333,1,0)T.Position=UDim2.new(0.37510705,0,0.710606456,0)T.Size=UDim2.new(0,129,0,32)T.Font=Enum.Font.SourceSansBold;T.Text="LAMBORGHINI"T.TextColor3=Color3.new(1,1,1)T.TextScaled=true;T.TextSize=20;T.TextStrokeTransparency=0;T.TextWrapped=true;T.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(146.568039,17.6188164,775.127197)+Vector3.new(1,0,0)end end)U.Name="BUGGATI"U.Parent=C;U.BackgroundColor3=Color3.new(0.333333,1,0)U.Position=UDim2.new(0.694256663,0,0.861549973,0)U.Size=UDim2.new(0,129,0,32)U.Font=Enum.Font.SourceSansBold;U.Text="BUGGATI"U.TextColor3=Color3.new(1,1,1)U.TextScaled=true;U.TextSize=20;U.TextStrokeTransparency=0;U.TextWrapped=true;U.MouseButton1Down:connect(function()for h=1,32 do wait(.08)game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new(262.065,15.756,1360.726)+Vector3.new(1,0,0)end end)V.Name="JAILBREAK V5.5"V.Parent=A;V.Active=true;V.BackgroundColor3=Color3.new(0,0.333333,1)V.BorderColor3=Color3.new(0.333333,1,0.498039)V.BorderSizePixel=3;V.Position=UDim2.new(0,0,-0.149445608,0)V.Selectable=true;V.Size=UDim2.new(0,493,0,35)V.Font=Enum.Font.Cartoon;V.Text="JAILBREAK V5.5"V.TextColor3=Color3.new(1,1,1)V.TextSize=35;V.TextWrapped=true;W.Name="EXIT"W.Parent=A;W.BackgroundColor3=Color3.new(1,0,0)W.Position=UDim2.new(0.0121785337,0,-0.136448875,0)W.Size=UDim2.new(0,62,0,25)W.Font=Enum.Font.Cartoon;W.Text="EXIT"W.TextColor3=Color3.new(1,1,1)W.TextScaled=true;W.TextSize=14;W.TextStrokeTransparency=0;W.TextWrapped=true;W.MouseButton1Click:connect(function()z:Destroy()end)X.Name="CLOSE"X.Parent=A;X.BackgroundColor3=Color3.new(1,0,0)X.BackgroundTransparency=1;X.Position=UDim2.new(0.877329826,0,-0.151213929,0)X.Size=UDim2.new(0,60,0,35)X.Font=Enum.Font.Cartoon;X.Text="X"X.TextColor3=Color3.new(1,0,0)X.TextScaled=true;X.TextSize=14;X.TextStrokeTransparency=2;X.TextWrapped=true;X.MouseButton1Down:connect(function()aq.Visible=true;A.Visible=false end)Y.Name="AutoStuff"Y.Parent=A;Y.BackgroundColor3=Color3.new(0,0.333333,1)Y.BorderSizePixel=0;Y.Position=UDim2.new(0,0,0.147778317,0)Y.Selectable=true;Y.Size=UDim2.new(0,492,0,315)Y.Visible=false;Z.Name="AUTOARREST"Z.Parent=Y;Z.BackgroundColor3=Color3.new(0.333333,1,0)Z.Position=UDim2.new(0.0545465723,0,0.29886803,0)Z.Size=UDim2.new(0,438,0,43)Z.Font=Enum.Font.Cartoon;Z.Text="AutoArrest "Z.TextScaled=true;Z.TextSize=35;Z.TextWrapped=true;Z.MouseButton1Down:connect(function()local ar=game.Players.LocalPlayer;wait(0.5)for h,y in pairs(game.Teams.Criminal:GetPlayers())do repeat wait()ar.Character.HumanoidRootPart.CFrame=y.Character.HumanoidRootPart.CFrame*CFrame.new(0,0,1)until y.Team.Name~="Criminal"end end)_.Name="JewelryStatus"_.Parent=Y;_.BackgroundColor3=Color3.new(0,0,1)_.Position=UDim2.new(0.0241232216,0,0.856521845,0)_.Size=UDim2.new(0,129,0,36)_.Font=Enum.Font.SourceSans;_.Text="Jewelry:"_.TextColor3=Color3.new(0,0,0)_.TextSize=14;a0.Name="BankStatus"a0.Parent=Y;a0.BackgroundColor3=Color3.new(0,0,1)a0.Position=UDim2.new(0.711155295,0,0.856521845,0)a0.Size=UDim2.new(0,129,0,36)a0.Font=Enum.Font.SourceSans;a0.Text="Bank:"a0.TextColor3=Color3.new(0,0,0)a0.TextSize=14;a1.Name="BankAutoRobBtn"a1.Parent=Y;a1.BackgroundColor3=Color3.new(0,1,0)a1.Position=UDim2.new(0.0526274405,0,0.0829190686,0)a1.Size=UDim2.new(0,437,0,44)a1.Font=Enum.Font.Cartoon;a1.Text="Bank Auto Rob"a1.TextScaled=true;a1.TextSize=14;a1.TextWrapped=true;a1.MouseButton1Click:connect(function()local as=workspace:FindFirstChild("Banks"):GetChildren()[1]local at=as.Extra.Sign;if at.Decal.Transparency==0 then game:GetService("StarterGui"):SetCore("SendNotification",{Title="Bank is closed!",Text="You need to wait for the bank to open!",Duration=7,Button1="Dismiss"})return end;local au=Vector3.new(at.Position.X,0,at.Position.Z)local f=b.Character.HumanoidRootPart;local av=Vector3.new(f.Position.X,0,f.Position.Z)if(au-av).magnitude>150 then local aw=Instance.new"BindableFunction"aw.OnInvoke=function(ax)if ax=="Teleport"then JailbreakTp(10,18,784)end end;game:GetService("StarterGui"):SetCore("SendNotification",{Title="You are too far!",Text="You need to get closer to the bank (use tp)",Duration=7,Button1="Dismiss",Button2="Teleport",Callback=aw})else RobTheBank()end end)a2.Name="GOTO"a2.Parent=Y;a2.BackgroundColor3=Color3.new(0.333333,1,0)a2.Position=UDim2.new(0.585034311,0,0.556010902,0)a2.Size=UDim2.new(0,169,0,39)a2.Font=Enum.Font.Cartoon;a2.Text="GOTO"a2.TextScaled=true;a2.TextSize=35;a2.TextWrapped=true;a2.MouseButton1Down:connect(function()local ay=a3.Text;local az=game:GetService("Players")[ay]local aA=game:GetService("Players").LocalPlayer;local s=a3.Text;if az then for h=1,20 do wait()aA.Character.HumanoidRootPart.CFrame=az.Character.HumanoidRootPart.CFrame+Vector3.new(0,3,0)end end end)a3.Name="TP PLAYER TEXT"a3.Parent=Y;a3.BackgroundColor3=Color3.new(0.333333,1,0)a3.Position=UDim2.new(0.0528455302,0,0.536507964,0)a3.Size=UDim2.new(0,200,0,50)a3.Font=Enum.Font.SourceSans;a3.Text="TP TO PLAYER                          (PUT PLAYERS NAME HERE)   "a3.TextColor3=Color3.new(0,0,0)a3.TextScaled=true;a3.TextSize=14;a3.TextWrapped=true;a4.Name="OTHERSTUFF"a4.Parent=A;a4.BackgroundColor3=Color3.new(0,0.333333,1)a4.BorderSizePixel=0;a4.Position=UDim2.new(0.00214594905,0,0.147778317,0)a4.Selectable=true;a4.Size=UDim2.new(0,491,0,315)a4.Visible=false;a5.Name="CARFLY(R)"a5.Parent=a4;a5.BackgroundColor3=Color3.new(0.333333,1,0)a5.Position=UDim2.new(0.0300429463,0,0.0438247025,0)a5.Size=UDim2.new(0,129,0,32)a5.Font=Enum.Font.SourceSansBold;a5.Text="CARFLY(R)"a5.TextColor3=Color3.new(1,1,1)a5.TextScaled=true;a5.TextSize=25;a5.TextStrokeTransparency=0;a5.TextWrapped=true;a5.MouseButton1Click:connect(function()local b=game:GetService("Players").LocalPlayer;local aB=b:GetMouse()aB.KeyDown:connect(function(aC)if aC:byte()==114 then plrh=game:GetService'Players'.LocalPlayer.Character:FindFirstChildOfClass'Humanoid'plrh:ChangeState('Jumping')wait()plrh:ChangeState('Seated')end end)end)a6.Name="BTOOLS"a6.Parent=a4;a6.BackgroundColor3=Color3.new(0.333333,1,0)a6.Position=UDim2.new(0.371244639,0,0.0438247025,0)a6.Size=UDim2.new(0,129,0,32)a6.Font=Enum.Font.SourceSansBold;a6.Text="BTOOLS"a6.TextColor3=Color3.new(1,1,1)a6.TextScaled=true;a6.TextSize=25;a6.TextStrokeTransparency=0;a6.TextWrapped=true;a6.MouseButton1Down:connect(function()game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Backpack,true)for aD,aE in pairs(game:GetService("Workspace"):GetChildren())do if aE.ClassName=="Part"then aE.Locked=false end;if aE.ClassName=="MeshPart"then aE.Locked=false end;if aE.ClassName=="UnionOperation"then aE.Locked=false end;if aE.ClassName=="Model"then for aD,aF in pairs(aE:GetChildren())do if aF.ClassName=="Part"then aF.Locked=false end;if aF.ClassName=="MeshPart"then aF.Locked=false end;if aF.ClassName=="UnionOperation"then aF.Locked=false end;if aF.ClassName=="Model"then for aD,aG in pairs(aF:GetChildren())do if aG.ClassName=="Part"then aG.Locked=false end;if aG.ClassName=="MeshPart"then aG.Locked=false end;if aG.ClassName=="UnionOperation"then aG.Locked=false end;if aG.ClassName=="Model"then for aD,aH in pairs(aG:GetChildren())do if aH.ClassName=="Part"then aH.Locked=false end;if aH.ClassName=="MeshPart"then aH.Locked=false end;if aH.ClassName=="UnionOperation"then aH.Locked=false end;if aH.ClassName=="Model"then end end end end end end end end;c=Instance.new("HopperBin",game:GetService("Players").LocalPlayer.Backpack)c.BinType=Enum.BinType.Hammer;c=Instance.new("HopperBin",game:GetService("Players").LocalPlayer.Backpack)c.BinType=Enum.BinType.Clone;c=Instance.new("HopperBin",game:GetService("Players").LocalPlayer.Backpack)c.BinType=Enum.BinType.Grab end)a7.Name="GRAVITY"a7.Parent=a4;a7.BackgroundColor3=Color3.new(0.333333,1,0)a7.Position=UDim2.new(0.7081545,0,0.36101082,0)a7.Size=UDim2.new(0,129,0,32)a7.Font=Enum.Font.SourceSansBold;a7.Text="GRAVITY"a7.TextColor3=Color3.new(1,1,1)a7.TextScaled=true;a7.TextSize=1;a7.TextStrokeTransparency=0;a7.TextWrapped=true;a7.MouseButton1Down:connect(function()if a7==true then a7=false;game.workspace.Gravity=196.2 else a7=true;game.workspace.Gravity=45 end end)a8.Name="INFINT FUEL"a8.Parent=a4;a8.BackgroundColor3=Color3.new(0.333333,1,0)a8.Position=UDim2.new(0.7081545,0,0.516245484,0)a8.Size=UDim2.new(0,129,0,32)a8.Font=Enum.Font.SourceSansBold;a8.Text="INFINITE FUEL"a8.TextColor3=Color3.new(1,1,1)a8.TextScaled=true;a8.TextSize=25;a8.TextStrokeTransparency=0;a8.TextWrapped=true;a8.MouseButton1Down:connect(function()game:GetService('Players').LocalPlayer.PlayerGui.MainGui.Nitro.Name="69696969"game:GetService('Players').LocalPlayer.PlayerGui.ProductGui.Nitro:ClearAllChildren()end)a9.Name="INFINTE AMMO"a9.Parent=a4;a9.BackgroundColor3=Color3.new(0.333333,1,0)a9.Position=UDim2.new(0.371244639,0,0.51569891,0)a9.Size=UDim2.new(0,129,0,32)a9.Font=Enum.Font.SourceSansBold;a9.Text="INFINTE AMMO"a9.TextColor3=Color3.new(1,1,1)a9.TextScaled=true;a9.TextSize=25;a9.TextStrokeTransparency=0;a9.TextWrapped=true;a9.MouseButton1Click:connect(function()local newcclosure=newcclosure or function(w)return w end;local getreg=debug.getregistry or getreg;if not getreg then warn("You Need Level 7 executor to use this")end;local aI;local aJ;local aK;local aL;local aM;for aN,aO in pairs(getreg())do if typeof(aO)=="table"then if aO.Pistol then aI=aO.Pistol;aJ=aO.Rifle;aK=aO.RocketLauncher;aL=aO.Shotgun;aM=aO.AK47 end end end;if aI then aI.MagSize=math.huge;aI.FireAuto=true;aI.FireFreq=5000;aI.BulletSpread=0;aI.BulletSpeed=5000;warn("Modded the pistol")end;if aJ then aJ.MagSize=math.huge;aJ.FireAuto=true;aJ.FireFreq=5000;aJ.BulletSpread=0;aJ.BulletSpeed=5000;warn("Modded the rifle")end;if aK then aK.MagSize=math.huge;aK.FireAuto=true;aK.FireFreq=5000;aK.BulletSpread=0;aK.BulletSpeed=5000;warn("Modded the Rocket Launcher")end;if aL then aL.MagSize=math.huge;aL.FireAuto=true;aL.FireFreq=5000;aL.BulletSpread=0;aL.BulletSpeed=5000;warn("Modded the Shotgun")end;if aM then aM.MagSize=math.huge;aM.FireAuto=true;aM.FireFreq=5000;aM.BulletSpread=0;aM.BulletSpeed=5000;warn("Modded the AK47")end end)aa.Name="M4A4"aa.Parent=a4;aa.BackgroundColor3=Color3.new(0.333333,1,0)aa.Position=UDim2.new(0.0300429463,0,0.193852752,0)aa.Size=UDim2.new(0,129,0,32)aa.Font=Enum.Font.SourceSansBold;aa.Text="M4A4"aa.TextColor3=Color3.new(1,1,1)aa.TextScaled=true;aa.TextSize=25;aa.TextStrokeTransparency=0;aa.TextWrapped=true;aa.MouseButton1Down:connect(function()local aP=game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position+Vector3.new(0,0,-3)a=Instance.new("Part",workspace)a.Anchored=true;a.Position=game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position+Vector3.new(0,0,-3)a.CanCollide=false;for h,y in pairs(game:GetService("Workspace").Givers:GetChildren())do if y.Name=="Station"then for a,aQ in pairs(y:GetChildren())do if aQ:IsA("StringValue")then if aQ.Value=="RifleSWAT"then y.CFrame=CFrame.new(aP)end end end end end end)ab.Name="NOCLIP[B]"ab.Parent=a4;ab.BackgroundColor3=Color3.new(0.333333,1,0)ab.Position=UDim2.new(0.7081545,0,0.194945842,0)ab.Size=UDim2.new(0,129,0,32)ab.Font=Enum.Font.SourceSansBold;ab.Text="NOCLIP[B]"ab.TextColor3=Color3.new(1,1,1)ab.TextScaled=true;ab.TextSize=35;ab.TextStrokeTransparency=0;ab.TextWrapped=true;ab.MouseButton1Down:connect(function()local aR=game:GetService("Players").LocalPlayer;local aS=aR:GetMouse()local aT=false;local aU=false;function b_noclip(aV)if aV=="b"then if aU==false then aT=true;aU=true elseif aU==true then aT=false;aU=false end end end;aS.KeyDown:connect(b_noclip)game:GetService("Players").LocalPlayer.Character.Head.Touched:connect(function(k)if k~=workspace.Terrain then if aT==true then k.CanCollide=false else k.CanCollide=true end end end)end)ac.Name="PISTOL"ac.Parent=a4;ac.BackgroundColor3=Color3.new(0.333333,1,0)ac.Position=UDim2.new(0.0300429165,0,0.359817058,0)ac.Size=UDim2.new(0,129,0,32)ac.Font=Enum.Font.SourceSansBold;ac.Text="PISTOL"ac.TextColor3=Color3.new(1,1,1)ac.TextScaled=true;ac.TextSize=25;ac.TextStrokeTransparency=0;ac.TextWrapped=true;ac.MouseButton1Down:connect(function()local aP=game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position+Vector3.new(0,0,-3)a=Instance.new("Part",workspace)a.Anchored=true;a.Position=game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position+Vector3.new(0,0,-3)a.CanCollide=false;for h,y in pairs(game:GetService("Workspace").Givers:GetChildren())do if y.Name=="Station"then for a,aQ in pairs(y:GetChildren())do if aQ:IsA("StringValue")then if aQ.Value=="Pistol"then y.CFrame=CFrame.new(aP)end end end end end end)ad.Name="REMOVE BUILDING"ad.Parent=a4;ad.BackgroundColor3=Color3.new(0.333333,1,0)ad.Position=UDim2.new(0.371244639,0,0.359817058,0)ad.Size=UDim2.new(0,129,0,32)ad.Font=Enum.Font.SourceSansBold;ad.Text="REMOVE BUILDING"ad.TextColor3=Color3.new(1,1,1)ad.TextScaled=true;ad.TextSize=25;ad.TextStrokeTransparency=0;ad.TextWrapped=true;ad.MouseButton1Down:connect(function()game:GetService("Workspace").Buildings:Destroy()end)ae.Name="REMOVEALL"ae.Parent=a4;ae.BackgroundColor3=Color3.new(0.333333,1,0)ae.Position=UDim2.new(0.371244639,0,0.193852752,0)ae.Size=UDim2.new(0,129,0,32)ae.Font=Enum.Font.SourceSansBold;ae.Text="REMOVEALL"ae.TextColor3=Color3.new(1,1,1)ae.TextScaled=true;ae.TextSize=25;ae.TextStrokeTransparency=0;ae.TextWrapped=true;ae.MouseButton1Down:connect(function()game.Workspace.Cells:Remove()game.Workspace.Museum.CaseLasers:Remove()game.Workspace.Museum.Lights:Remove()game.Workspace.Museum.Doors:Remove()game.Workspace.EscapeRoutes:Remove()for h,y in pairs(workspace.Doors:GetChildren())do y:Destroy()end end)ae.MouseButton1Down:connect(function()local aW=game:GetService("Workspace").Banks:GetChildren()aW[1].Lasers:Destroy()end)ae.MouseButton1Down:connect(function()local aX=game:GetService("Workspace").Jewelrys:GetChildren()for h=1,4 do local aY=aX[1].Model.BarbedWire;aY:Destroy()end end)ae.MouseButton1Down:connect(function()local aW=game:GetService("Workspace").Banks:GetChildren()aW[1].Door.Model:Destroy()end)af.Name="SHOTGUN"af.Parent=a4;af.BackgroundColor3=Color3.new(0.333333,1,0)af.Position=UDim2.new(0.0300429165,0,0.515698969,0)af.Size=UDim2.new(0,129,0,32)af.Font=Enum.Font.SourceSansBold;af.Text="SHOTGUN"af.TextColor3=Color3.new(1,1,1)af.TextScaled=true;af.TextSize=25;af.TextStrokeTransparency=0;af.TextWrapped=true;af.MouseButton1Down:connect(function()local aP=game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position+Vector3.new(0,0,-3)a=Instance.new("Part",workspace)a.Anchored=true;a.Position=game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.Position+Vector3.new(0,0,-3)a.CanCollide=false;for h,y in pairs(game:GetService("Workspace").Givers:GetChildren())do if y.Name=="Station"then for a,aQ in pairs(y:GetChildren())do if aQ:IsA("StringValue")then if aQ.Value=="Shotgun"then y.CFrame=CFrame.new(aP)end end end end end end)ag.Name="SPEED[X]"ag.Parent=a4;ag.BackgroundColor3=Color3.new(0.333333,1,0)ag.Position=UDim2.new(0.7081545,0,0.0433213115,0)ag.Size=UDim2.new(0,129,0,32)ag.Font=Enum.Font.SourceSansBold;ag.Text="SPEED[X]"ag.TextColor3=Color3.new(1,1,1)ag.TextScaled=true;ag.TextSize=25;ag.TextStrokeTransparency=0;ag.TextWrapped=true;ag.MouseButton1Down:connect(function()local aZ=game:GetService("Players").LocalPlayer;local a_=aZ:GetMouse()local b0=false;function x_walkspeed(aV)if aV=="x"then if b0==false then _G.WS=200;local b1=game:GetService("Players").LocalPlayer.Character.Humanoid;b1:GetPropertyChangedSignal("WalkSpeed"):Connect(function()b1.WalkSpeed=_G.WS end)b1.WalkSpeed=_G.WS;b0=true elseif b0==true then _G.WS=20;local b1=game:GetService("Players").LocalPlayer.Character.Humanoid;b1:GetPropertyChangedSignal("WalkSpeed"):Connect(function()b1.WalkSpeed=_G.WS end)b1.WalkSpeed=_G.WS;b0=false end end end;a_.KeyDown:connect(x_walkspeed)end)ah.Name="INFINITE JUMP"ah.Parent=a4;ah.BackgroundColor3=Color3.new(0.333333,1,0)ah.Position=UDim2.new(0.0300429165,0,0.676557302,0)ah.Size=UDim2.new(0,129,0,32)ah.Font=Enum.Font.SourceSansBold;ah.Text="INFINITE JUMP"ah.TextColor3=Color3.new(1,1,1)ah.TextScaled=true;ah.TextSize=25;ah.TextStrokeTransparency=0;ah.TextWrapped=true;ah.MouseButton1Down:connect(function()game:GetService("UserInputService").JumpRequest:connect(function()game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")end)end)ai.Name="GODMODE"ai.Parent=a4;ai.BackgroundColor3=Color3.new(0.333333,1,0)ai.Position=UDim2.new(0.371244639,0,0.675090253,0)ai.Size=UDim2.new(0,129,0,32)ai.Font=Enum.Font.SourceSansBold;ai.Text="GODMODE "ai.TextColor3=Color3.new(1,1,1)ai.TextScaled=true;ai.TextSize=25;ai.TextStrokeTransparency=0;ai.TextWrapped=true;ai.MouseButton1Down:connect(function()game:GetService("Players").LocalPlayer.Character.Humanoid.Name=1;local u=game:GetService("Players").LocalPlayer.Character["1"]:Clone()u.Parent=game:GetService("Players").LocalPlayer.Character;u.Name="Humanoid"wait(0.1)game:GetService("Players").LocalPlayer.Character["1"]:Destroy()game:GetService("Workspace").CurrentCamera.CameraSubject=game:GetService("Players").LocalPlayer.Character;game:GetService("Players").LocalPlayer.Character.Animate.Disabled=true;wait(0.1)game:GetService("Players").LocalPlayer.Character.Animate.Disabled=false;game:GetService("Players").LocalPlayer.Character.Humanoid.DisplayDistanceType="None"end)aj.Name="TPSTORE"aj.Parent=a4;aj.BackgroundColor3=Color3.new(0.333333,1,0)aj.Position=UDim2.new(0.7081545,0,0.675090253,0)aj.Size=UDim2.new(0,129,0,32)aj.Font=Enum.Font.SourceSansBold;aj.Text="TPSTORE"aj.TextColor3=Color3.new(1,1,1)aj.TextSize=29;aj.TextStrokeTransparency=0;aj.TextWrapped=true;aj.MouseButton1Click:connect(function()local a=getfenv()[string.char(118,110,113,106,114,111,96,98,100)]:FindFirstChild(string.char(82,108,96,107,107,82,115,110,113,100,114))if not a then return end;for h,y in pairs(a:GetChildren())do y[string.char(83,113,96,109,114,111,96,113,100,109,98,120)]=0;y[string.char(66,69,113,96,108,100)]=b[string.char(66,103,96,113,96,98,115,100,113)]:WaitForChild(string.char(71,116,108,96,109,110,104,99,81,110,110,115,79,96,113,115))[string.char(66,69,113,96,108,100)]*CFrame.new(math.random(-3,3),0,math.random(-3,3))end end)ak.Name="CLICKTP[CTRL]"ak.Parent=a4;ak.BackgroundColor3=Color3.new(0.333333,1,0)ak.Position=UDim2.new(0.371244639,0,0.837545097,0)ak.Size=UDim2.new(0,129,0,32)ak.Font=Enum.Font.SourceSansBold;ak.Text="CLICKTP(CTRL)"ak.TextColor3=Color3.new(1,1,1)ak.TextScaled=true;ak.TextSize=25;ak.TextStrokeTransparency=0;ak.TextWrapped=true;ak.MouseButton1Down:connect(function()loadstring(game:GetObjects("rbxassetid://956305503")[1].Source)()end)al.Name="KEYCARD"al.Parent=a4;al.BackgroundColor3=Color3.new(0.333333,1,0)al.Position=UDim2.new(0.0300429203,0,0.837545037,0)al.Size=UDim2.new(0,129,0,32)al.Font=Enum.Font.SourceSansBold;al.Text="KEYCARD"al.TextColor3=Color3.new(1,1,1)al.TextScaled=true;al.TextSize=25;al.TextStrokeTransparency=0;al.TextWrapped=true;al.MouseButton1Down:connect(function()game.Players.LocalPlayer.TeamValue.Value="Police"end)am.Name="VEHICLESPEED"am.Parent=a4;am.BackgroundColor3=Color3.new(0.333333,1,0)am.Position=UDim2.new(0.7081545,0,0.837545156,0)am.Size=UDim2.new(0,129,0,32)am.Font=Enum.Font.SourceSansBold;am.Text="VEHICLE SPEED"am.TextColor3=Color3.new(1,1,1)am.TextScaled=true;am.TextSize=25;am.TextStrokeTransparency=0;am.TextWrapped=true;am.MouseButton1Down:connect(function()loadstring(game:GetObjects("rbxassetid://979093131")[1].Source)()end)an.Name="AUTOSTUFF"an.Parent=A;an.BackgroundColor3=Color3.new(1,0.333333,0)an.Position=UDim2.new(0.362660944,0,0.0237288196,0)an.Size=UDim2.new(0,134,0,33)an.Font=Enum.Font.SourceSansBold;an.Text="AUTOSTUFF"an.TextColor3=Color3.new(1,1,1)an.TextScaled=true;an.TextSize=23;an.TextStrokeTransparency=0;an.TextWrapped=true;an.MouseButton1Down:connect(function()Y.Visible=true;C.Visible=false;a4.Visible=false end)ao.Name="STUFF"ao.Parent=A;ao.BackgroundColor3=Color3.new(1,0.333333,0)ao.Position=UDim2.new(0.697542429,0,0.0237288177,0)ao.Size=UDim2.new(0,135,0,33)ao.Font=Enum.Font.SourceSansBold;ao.Text="STUFF"ao.TextColor3=Color3.new(1,1,1)ao.TextScaled=true;ao.TextSize=23;ao.TextStrokeTransparency=0;ao.TextWrapped=true;ao.MouseButton1Down:connect(function()a4.Visible=true;Y.Visible=false;C.Visible=false end)ap.Name="TELEPORTS"ap.Parent=A;ap.BackgroundColor3=Color3.new(1,0.333333,0)ap.Position=UDim2.new(0.0257363915,0,0.0237288177,0)ap.Size=UDim2.new(0,134,0,33)ap.Font=Enum.Font.SourceSansBold;ap.Text="TELEPORTS"ap.TextColor3=Color3.new(1,1,1)ap.TextScaled=true;ap.TextSize=23;ap.TextStrokeTransparency=0;ap.TextWrapped=true;ap.MouseButton1Down:connect(function()C.Visible=true;Y.Visible=false;a4.Visible=false end)aq.Name="Open"aq.Parent=z;aq.BackgroundColor3=Color3.new(0,0,1)aq.Position=UDim2.new(0,0,0.224105462,0)aq.Size=UDim2.new(0,79,0,27)aq.Visible=false;aq.Font=Enum.Font.Cartoon;aq.Text="OPEN"aq.TextColor3=Color3.new(1,1,1)aq.TextScaled=true;aq.TextSize=14;aq.TextWrapped=true;aq.MouseButton1Down:connect(function()aq.Visible=false;A.Visible=true end)pcall(function()local b2=workspace:FindFirstChild("Jewelrys"):GetChildren()[1]local at=b2.Extra.Sign.Decal;at:GetPropertyChangedSignal("Transparency"):Connect(function()if at.Transparency~=0 then _.Text="Jewelry:Open"_.TextColor3=Color3.new(0,1,0)_.TextColor3=Color3.new(0,1,0)local aw=Instance.new("BindableFunction")aw.OnInvoke=function(ax)if ax=="Teleport"then JailbreakTp(142,18,1365)end end;game:GetService("StarterGui"):SetCore("SendNotification",{Title="Jewelry is ready!",Text="Jewelry is ready!",Duration=15,Button1="Dismiss",Button2="Teleport",Callback=aw})else _.Text="Jewelry:Closed"_.TextColor3=Color3.new(1,0,0)end end)_.Text=at.Transparency==0 and"Jewelry:Closed"or"Jewelry:Open"_.TextColor3=at.Transparency==0 and Color3.new(1,0,0)or Color3.new(0,1,0)end)pcall(function()local as=workspace:FindFirstChild("Banks"):GetChildren()[1]local at=as.Extra.Sign.Decal;at:GetPropertyChangedSignal("Transparency"):Connect(function()if at.Transparency~=0 then a0.Text="Bank:Open"a0.TextColor3=Color3.new(0,1,0)local aw=Instance.new("BindableFunction")aw.OnInvoke=function(ax)if ax=="Teleport"then JailbreakTp(10,18,784)end end;game:GetService("StarterGui"):SetCore("SendNotification",{Title="Bank is ready!",Text="Bank is ready!",Duration=15,Button1="Dismiss",Button2=(Vector3.new(at.Parent.Position.X,0,at.Parent.Position.Z)-Vector3.new(b.Character.HumanoidRootPart.Position.X,0,b.Character.HumanoidRootPart.Position.Z)).magnitude&lt;150 and"AutoRob"or"Teleport",Callback=aw})else a0.Text="Bank:Closed"a0.TextColor3=Color3.new(1,0,0)end end)a0.Text=at.Transparency==0 and"Bank:Closed"or"Bank:Open"a0.TextColor3=at.Transparency==0 and Color3.new(1,0,0)or Color3.new(0,1,0)end)wait(0.1)game.CoreGui.JailBreak.Main:TweenPosition(UDim2.new(0,100,0,270),'Out','Bounce',2,true)wait(0.6)game.CoreGui.JailBreak.Main:TweenPosition(UDim2.new(0,835,0,270),'Out','Bounce',2,true)
