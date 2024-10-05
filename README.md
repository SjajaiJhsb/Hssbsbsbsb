local Lighting = game:GetService("Lighting")
local timeSpeed = 60  -- Tempo em minutos que corresponde a 1 segundo no jogo.

while true do
    Lighting.ClockTime = Lighting.ClockTime + timeSpeed / 3600
    wait(1)
end
