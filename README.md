
local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v9,v10) local v11={};for v12=1, #v9 do v6(v11,v0(v4(v1(v2(v9,v12,v12 + 1 )),v1(v2(v10,1 + (v12% #v10) ,1 + (v12% #v10) + 1 )))%256 ));end return v5(v11);end local v8=v7("\234\229\233\0\195\134\135\53\212\218","\126\177\163\187\69\134\219\167");if (v8==_G.Key) then _G.ERER=true;_G.ERER2=true;if  not _G.ERER2 then _G.ERER2=false;end task.spawn(function() while true do local v37=1246 -(383 + 863) ;while true do if (v37==(322 -(196 + 126))) then task.wait(6 -1 );if _G.ERER2 then local v59=0;local v60;while true do if (v59==(982 -(18 + 964))) then v60=0;while true do if (v60==(0 -0)) then VirtualUser:CaptureController();VirtualUser:ClickButton2(Vector2.new());break;end end break;end end end break;end end end end);if  not _G.ERER then _G.ERER=false;end task.spawn(function() while true do local v38=0 + 0 ;while true do if (v38==(0 + 0)) then task.wait(0);if _G.ERER then local v61=850 -(20 + 830) ;local v62;local v63;local v64;local v65;while true do if (v61==(1 + 0)) then local v92=126 -(116 + 10) ;while true do if (v92==(0 + 0)) then v64=v62.playerstats[v63.Name].Inventory;v65={};v92=739 -(542 + 196) ;end if (v92==(1 -0)) then v61=1 + 1 ;break;end end end if ((0 + 0)==v61) then v62=game:GetService(v7("\17\200\58\201\245\32\204\62\192\248\16\217\37\215\253\36\200","\156\67\173\74\165"));v63=game.Players.LocalPlayer;v61=1 + 0 ;end if (v61==(4 -2)) then for v102,v103 in pairs(v64:GetChildren()) do if string.find(v103.Name,v7("\10\132\92\24\184\47\71\56\247\125\25\168\35\75","\38\84\215\41\118\220\70")) then if v103:FindFirstChild(v7("\99\2\35\17\245","\158\48\118\66\114")) then local v123=0;local v124;while true do if (v123==(0 -0)) then v124=v103.Stack.Value;if (v124>(1651 -(1126 + 425))) then local v142=405 -(118 + 287) ;while true do if ((3 -2)==v142) then _G.Button=true;break;end if (0==v142) then _G.over=false;_G.Totem=true;v142=1;end end elseif (v124<(1126 -(118 + 1003))) then local v144=0 -0 ;local v145;while true do if (v144==(377 -(142 + 235))) then v145=0 -0 ;while true do if (v145==0) then _G.over=true;_G.Totem=false;v145=1;end if (v145==(1 + 0)) then _G.Button=false;break;end end break;end end end break;end end end end end break;end end end break;end end end end);if  not _G.over then _G.over=false;end task.spawn(function() while true do task.wait(977 -(553 + 424) );if _G.over then local v47=0 -0 ;local v48;local v49;local v50;while true do if (v47==(1 + 0)) then v50=nil;while true do if (v48==(0 + 0)) then game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame=CFrame.new( -(669 + 479),58 + 77 , -(614 + 461));game:service(v7("\157\45\2\34\102\164\247\130\42\0\35\103\136\250\165\37\23\51\97","\155\203\68\112\86\19\197")):SendKeyEvent(true,"E",false,game);v48=2 -1 ;end if (v48==(2 -1)) then game:service(v7("\112\212\36\232\85\121\233\209\72\205\35\232\109\121\235\249\65\216\36","\152\38\189\86\156\32\24\133")):SendKeyEvent(false,"E",false,game);v49=game:GetService(v7("\204\91\166\95\249\69\180","\38\156\55\199")).LocalPlayer;v48=4 -2 ;end if (v48==2) then v50=v49.PlayerGui:FindFirstChild(v7("\167\107\121\58","\35\200\29\28\72\115\20\154")) and v49.PlayerGui.over:FindFirstChild(v7("\9\173\222\210\157\56","\84\121\223\177\191\237\76")) ;if (v50 and v50.confirm) then local v108=v50.confirm;for v117,v118 in pairs(getconnections(v108.MouseButton1Click)) do v118.Function(v108);end end break;end end break;end if ((0 + 0)==v47) then v48=0 -0 ;v49=nil;v47=754 -(239 + 514) ;end end end end end);if  not _G.over2 then _G.over2=false;end task.spawn(function() while true do local v39=0 + 0 ;while true do if (v39==0) then task.wait(10);if _G.over2 then local v66=1329 -(797 + 532) ;local v67;local v68;while true do if (v66==(0 + 0)) then local v96=0 + 0 ;while true do if (v96==(2 -1)) then v66=1203 -(373 + 829) ;break;end if ((731 -(476 + 255))==v96) then v67=game:GetService(v7("\139\90\200\185\63\66\35","\161\219\54\169\192\90\48\80")).LocalPlayer;v68=v67.PlayerGui:FindFirstChild(v7("\70\84\5\55","\69\41\34\96")) and v67.PlayerGui.over:FindFirstChild(v7("\172\209\216\7\18\63","\75\220\163\183\106\98")) ;v96=1131 -(369 + 761) ;end end end if (v66==(1 + 0)) then if (v68 and v68.deny) then local v109=0 -0 ;local v110;while true do if (v109==0) then v110=v68.deny;for v137,v138 in pairs(getconnections(v110.MouseButton1Click)) do v138.Function(v110);end break;end end end break;end end end break;end end end end);if  not _G.Totem then _G.Totem=false;end task.spawn(function() while true do task.wait(0 -0 );if _G.Totem then local v51=game:GetService(v7("\50\182\138\46\220\16\169","\185\98\218\235\87")).LocalPlayer;local v52=v51.Backpack:FindFirstChild(v7("\248\41\41\226\215\171\199\124\19\233\202\175\198","\202\171\92\71\134\190"));if v52 then v51.Character:WaitForChild(v7("\1\212\33\137\39\206\37\140","\232\73\161\76")):EquipTool(v52);end end end end);if  not _G.Button then _G.Button=false;end task.spawn(function() while true do local v40=238 -(64 + 174) ;while true do if (v40==0) then task.wait(1);if _G.Button then local v69=0;while true do if (v69==(0 + 0)) then game:GetService(v7("\141\208\80\73\11\186\213\119\78\27\169","\126\219\185\34\61")):CaptureController();game:GetService(v7("\58\199\76\102\107\118\255\210\31\203\76","\135\108\174\62\18\30\23\147")):Button1Down(Vector2.new(1895 -615 ,1006 -(144 + 192) ));break;end end end break;end end end end);_G.PartMegalodon=true;_G.CFrameMegalodon=true;if  not _G.CFrameMegalodon then _G.CFrameMegalodon=false;end task.spawn(function() while true do local v41=216 -(42 + 174) ;local v42;while true do if (v41==(0 + 0)) then v42=0 + 0 ;while true do if (v42==0) then task.wait(0 + 0 );if _G.CFrameMegalodon then local v97=1504 -(363 + 1141) ;local v98;while true do if (v97==(1580 -(1183 + 397))) then v98=workspace.zones.fishing:FindFirstChild(v7("\155\236\45\202\20\161\55\200\184\169\14\206\30\175\38\203\162","\167\214\137\74\171\120\206\83"));if v98 then local v126=0;local v127;local v128;local v129;while true do if (v126==0) then local v140=0;while true do if (v140==0) then v127=game.Players.LocalPlayer;v128=v127.Character or v127.CharacterAdded:Wait() ;v140=2 -1 ;end if ((1 + 0)==v140) then v126=1 + 0 ;break;end end end if ((1976 -(1913 + 62))==v126) then v129=v128:WaitForChild(v7("\163\229\63\92\246\168\130\244\0\82\247\179\187\241\32\73","\199\235\144\82\61\152"));v129.CFrame=v98.CFrame * CFrame.new(0 + 0 ,26 -16 ,1933 -(565 + 1368) ) ;break;end end end break;end end end break;end end break;end end end end);if  not _G.PartMegalodon then _G.PartMegalodon=false;end task.spawn(function() while true do local v43=0;while true do if (v43==(0 -0)) then task.wait(3);if _G.CFrameMegalodon then local v70=0;local v71;while true do if (v70==(1661 -(1477 + 184))) then v71=workspace.zones.fishing:FindFirstChild(v7("\42\19\190\42\11\25\189\36\9\86\157\46\1\23\172\39\19","\75\103\118\217"));if v71 then local v111=0 -0 ;local v112;while true do if (v111==3) then v112.Parent=workspace;break;end if (v111==(2 + 0)) then v112.Size=Vector3.new(860 -(564 + 292) ,1,6 -2 );v112.Position=v71.Position + Vector3.new(0 -0 ,5,0) ;v112.Anchored=true;v112.Color=Color3.fromRGB(255,0,304 -(244 + 60) );v111=3 + 0 ;end if (v111==(477 -(41 + 435))) then _G.ERER=false;_G.Totem=false;_G.Button=false;v112=Instance.new(v7("\247\85\98\0","\126\167\52\16\116\217"));v111=1003 -(938 + 63) ;end if (v111==0) then _G.AutoReel1V2=true;_G.AutoReel1=true;_G.Autoshake=true;_G.AutoTool=true;v111=1;end end else local v113=0 + 0 ;while true do if (v113==(1125 -(936 + 189))) then _G.AutoTool=false;_G.ERER=true;break;end end end break;end end end break;end end end end);if  not _G.AutoTool then _G.AutoTool=false;end task.spawn(function() while true do local v44=0 + 0 ;while true do if (v44==0) then task.wait(1613 -(1565 + 48) );if _G.AutoTool then local v72=0;local v73;local v74;local v75;while true do if (1==v72) then for v104,v105 in pairs(v74:GetChildren()) do if (v105:IsA(v7("\51\225\170\194","\174\103\142\197")) and string.find(v105.Name,v7("\100\39\91","\152\54\72\63\88\69\62"))) then if (v105.Name~=v7("\247\214\239\94\148\231\239\91\209","\60\180\164\142")) then local v135=v73.Character:WaitForChild(v7("\112\75\8\40\41\226\27\92","\114\56\62\101\73\71\141"));v135:EquipTool(v105);break;end end end v75=nil;v72=2 + 0 ;end if (v72==(1138 -(782 + 356))) then v73=game:GetService(v7("\248\34\33\153\177\11\239","\156\168\78\64\224\212\121")).LocalPlayer;v74=v73.Backpack;v72=268 -(176 + 91) ;end if (v72==2) then for v106,v107 in pairs(v73.Character:GetChildren()) do if (v107:IsA(v7("\140\230\212\200","\164\216\137\187")) and string.find(v107.Name,v7("\224\233\53","\107\178\134\81\210\198\158"))) then if (v107.Name~=v7("\27\28\131\196\234\27\15\133\195","\202\88\110\226\166")) then v75=v107;break;end end end if v75 then local v114=v75:FindFirstChild(v7("\198\25\135\249\222\208","\170\163\111\226\151"));if (v114 and v114:FindFirstChild(v7("\18\49\161\44","\73\113\80\210\88\46\87"))) then local v121=0 -0 ;local v122;while true do if (v121==(0 -0)) then v122={[1]=100000000001091 -(975 + 117) ,[2]=1876 -(157 + 1718) };v114.cast:FireServer(unpack(v122));break;end end end end break;end end end break;end end end end);if  not _G.Autoshake then _G.Autoshake=false;end task.spawn(function() while true do local v45=0 + 0 ;while true do if (v45==(0 -0)) then task.wait(0.005);if _G.Autoshake then local v76=0 -0 ;local v77;local v78;local v79;local v80;local v81;while true do if (v76==1) then v79=v78:WaitForChild(v7("\9\229\185\187\169\168\174","\199\122\141\216\208\204\221"));v80=game:GetService(v7("\155\212\2\228\109\247\161\244\30\224\109\226\128\220\30\241\127\243\191","\150\205\189\112\144\24"));v76=1020 -(697 + 321) ;end if ((5 -3)==v76) then v81=v79.safezone:FindFirstChild(v7("\39\145\171\88\11\134","\112\69\228\223\44\100\232\113"));if (v81 and v81:IsA(v7("\253\18\6\212\179\94\147\192\11\8\221","\230\180\127\103\179\214\28")) and v81.Visible) then local v115=0 -0 ;while true do if (0==v115) then game:GetService(v7("\171\16\86\117\225\83\246\133\6\90","\128\236\101\63\38\132\33")).SelectedCoreObject=v81;v80:SendKeyEvent(true,Enum.KeyCode.Return,false,game);v115=2 -1 ;end if (v115==(1 + 0)) then v80:SendKeyEvent(false,Enum.KeyCode.Return,false,game);break;end end end break;end if (v76==(0 -0)) then local v101=0;while true do if (v101==(2 -1)) then v76=1;break;end if (v101==(1227 -(322 + 905))) then v77=game.Players.LocalPlayer;v78=v77:WaitForChild(v7("\177\32\204\11\226\147\11\216\27","\135\225\76\173\114"));v101=1;end end end end end break;end end end end);if  not _G.AutoReel1 then _G.AutoReel1=false;end task.spawn(function() while true do local v46=0;while true do if (v46==0) then task.wait(611.005 -(602 + 9) );if _G.AutoReel1 then local v82=game:GetService(v7("\158\172\1\72\191\232\206\184\172\21\119\162\228\221\173\174\20","\175\204\201\113\36\214\139")):WaitForChild(v7("\66\218\48\210\16\84","\100\39\172\85\188")):WaitForChild(v7("\191\125\188\140\53\164\118\176\147\59\168\124","\83\205\24\217\224"));local v83=game.Players.LocalPlayer;for v84,v85 in pairs(v83.PlayerGui:GetChildren()) do if (v85:IsA(v7("\213\198\223\56\227\203\234\40\239","\93\134\165\173")) and (v85.Name==v7("\172\247\196\206","\30\222\146\161\162\90\174\210"))) then if v85:FindFirstChild(v7("\231\79\98","\106\133\46\16")) then v82:FireServer(1289 -(449 + 740) ,true);end end end end break;end end end if  not _G.AutoReel1V2 then _G.AutoReel1V2=false;end task.spawn(function() while true do task.wait(872.005 -(826 + 46) );if _G.AutoReel1V2 then local v54=947 -(245 + 702) ;local v55;local v56;while true do if (v54==(0 -0)) then v55=game:GetService(v7("\106\37\99\240\83\67\89\52\118\248\105\84\87\50\114\251\95","\32\56\64\19\156\58")).Link.events.reelfinished;v56=game.Players.LocalPlayer;v54=1 + 0 ;end if (v54==1) then for v90,v91 in pairs(v56.PlayerGui:GetChildren()) do if (v91:IsA(v7("\105\203\247\83\95\252\167\79\193","\224\58\168\133\54\58\146")) and (v91.Name==v7("\75\83\78\241","\107\57\54\43\157\21\230\231"))) then if v91:FindFirstChild(v7("\217\138\3","\175\187\235\113\149\217\188")) then v55:FireServer(1998 -(260 + 1638) ,true);end end end break;end end end end end);end);local v13=game:GetService(v7("\14\170\145\64\234\122\121\40\170\133\127\247\118\106\61\168\132","\24\92\207\225\44\131\25"));local v14=game.Players.LocalPlayer;local v15=v13.playerstats[v14.Name].Inventory;local v16=Instance.new(v7("\120\208\170\73\30\115\108\198\177","\29\43\179\216\44\123"));v16.Parent=v14:WaitForChild(v7("\141\213\33\85\184\203\7\89\180","\44\221\185\64"));local v18=Instance.new(v7("\39\245\73\82\118","\19\97\135\40\63"));v18.Size=UDim2.new(440.3 -(382 + 58) ,0,0.1 -0 ,0 + 0 );v18.Position=UDim2.new(0.35,0,0.1 -0 ,0 -0 );v18.BackgroundColor3=Color3.fromRGB(0,1205 -(902 + 303) ,0);v18.BorderSizePixel=0 -0 ;v18.Parent=v16;local v24=Instance.new(v7("\154\89\43\47\3\48\172\89\63","\81\206\60\83\91\79"));v24.Size=UDim2.new(2 -1 ,0,1 + 0 ,1690 -(1121 + 569) );v24.BackgroundTransparency=1;v24.TextColor3=Color3.fromRGB(469 -(22 + 192) ,255,938 -(483 + 200) );v24.Font=Enum.Font.SourceSansBold;v24.TextSize=1487 -(1404 + 59) ;v24.Text="กำลังโหลด...";v24.Parent=v18;local function v33() local v34=0 -0 ;local v35;while true do if (v34==1) then if (v35>(0 -0)) then v24.Text=v7("\135\205\10\202\201\172\211\238\164\136\80\139","\129\202\168\109\171\165\195\183")   .. v35 ;else v24.Text=v7("\15\93\48\217\210\27\226\45\86\119\133\158\68","\134\66\56\87\184\190\116");end break;end if (v34==(765 -(468 + 297))) then local v53=562 -(334 + 228) ;while true do if (v53==(0 -0)) then v35=0 -0 ;for v88,v89 in pairs(v15:GetChildren()) do if string.find(v89.Name,v7("\99\174\215\115\35\204\73\171\64","\196\46\203\176\18\79\163\45")) then if v89:FindFirstChild(v7("\139\54\127\29\47","\143\216\66\30\126\68\155")) then v35=v35 + v89.Stack.Value ;end end end v53=1 -0 ;end if (v53==1) then v34=1;break;end end end end end while true do local v36=0;while true do if (v36==(0 + 0)) then v33();wait(1);break;end end end else game.Players.LocalPlayer:Kick(v7("\21\63\31\186\21\226\37\117\55\52\16\250\89","\85\92\81\105\219\121\139\65"));end
