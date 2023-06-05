# BD-P3-CASO-2
1*) π Correo,Nom PERS
2*) π Nom CURSO
3*) σ Ch > 40 CURSO
4*) σ Ch ≥ 40 ∧ Ch ≤ 45 CURSO
5*) π nombre_curso ← Nom, Tema (CURSO ⨝ TEMAS)
6*) π Correo,Nom (PERS ⨝ π Correo DICTA)
7*)
8*) A= ρ nomC ← Nom DICTA
    A ⨝ PERS
9*) PERS ⨝ (π Correo σ Nom='Python I' DICTA)
10*) π Correo,Nom (PERS ⨝ (π Correo σ Nom='Python I' ∨ Nom='Python II' DICTA))
11*) PERS ⨝ ((π Correo σ Nom='Python I' DICTA) ∩ (π Correo σ Nom='Python II' DICTA))
12*)
13*) PERS ⨝ (π Correo σ Nom='Kotlin I' INSC)
14*) PERS ⨝ (π Correo σ Nom='Kotlin II' INSC)
