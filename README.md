Rubywarrior-level-3
===================
class Player
  def play_turn(warrior)
 
 if warrior.feel.enemy?
        warrior.attack!
        else
      if warrior.health >7
        warrior.walk!
      else
          warrior.rest!
      end
    end
 
  end
end
