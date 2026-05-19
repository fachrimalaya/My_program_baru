# My_program
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>

<script>
const supabaseUrl = 'https://oojidxnmreehgkyawaaa.supabase.co'

const supabaseKey = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Im9vamlkeG5tcmVlaGdreWF3YWFhIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NzM4MzQxMDEsImV4cCI6MjA4OTQxMDEwMX0.9VMLifRBhO52A6FopWg1f1-yEnUDpFwSPlvPnj1XtKM'

const supabase = window.supabase.createClient(
    supabaseUrl,
    supabaseKey
)

console.log("Supabase Connected!")
</script>