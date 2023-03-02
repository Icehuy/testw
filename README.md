           CircleInline.Radius = library.flags["silent_fovr"]
           CircleInline.Thickness = 2
           CircleInline.Position = Vector2.new(Mouse.X, Mouse.Y + 36)
           CircleInline.Transparency = 1
           CircleInline.Color = Color3.fromRGB(255, 255, 255)
           CircleInline.Visible = library.flags["silent_showfov"]
           CircleInline.ZIndex = 2
        
           CircleOutline.Radius = library.flags["silent_fovr"]
           CircleOutline.Thickness = 4
           CircleOutline.Position = Vector2.new(Mouse.X, Mouse.Y + 36)
           CircleOutline.Transparency = 1
           CircleOutline.Color = Color3.new()
           CircleOutline.Visible = library.flags["silent_showfov"]
           CircleOutline.ZIndex = 1
        
           legit_target = GetClosest(library.flags["silent_fovr"])
